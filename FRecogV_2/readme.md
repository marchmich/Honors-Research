<div id="header"><p style="color:#3364ff; text-align:center; font-weight:bold; font-family:verdana; font-size:25px;">Image Recognition</p></div>

[licenseBDG]: https://img.shields.io/badge/License-CC-orange?style=plastic
[license]: https://creativecommons.org/licenses/by-nc-sa/3.0/deed.en

[mywebsiteBDG]:https://img.shields.io/badge/website-jaorduz.github.io-0abeeb?style=plastic
[mywebsite]: https://jaorduz.github.io/

[mygithubBDG-jaorduz]: https://img.shields.io/badge/jaorduz-repos-blue?logo=github&label=jaorduz&style=plastic
[mygithub-jaorduz]: https://github.com/jaorduz/

[mygithubBDG-jaorduc]: https://img.shields.io/badge/jaorduc-repos-blue?logo=github&label=jaorduc&style=plastic 
[mygithub-jaorduc]: https://github.com/jaorduc/

[myXprofileBDG]: https://img.shields.io/static/v1?label=Follow&message=jaorduc&color=2ea44f&style=plastic&logo=X&logoColor=black
[myXprofile]:https://twitter.com/jaorduc


[![website - jaorduz.github.io][mywebsiteBDG]][mywebsite]
[![Github][mygithubBDG-jaorduz]][mygithub-jaorduz]
[![Github][mygithubBDG-jaorduc]][mygithub-jaorduc]
[![Follow @jaorduc][myXprofileBDG]][myXprofile]
[![CC License][licenseBDG]][license]

---

<p style="text-align:right; font-family:verdana;"><a href="mywebsite" style="color:#3364ff; text-decoration:none;">@Javier Orduz</a></p>    


---

# The folder tree

In the main folder put a unknown.jpg image.

The following shows the tree:

face_recognizer/
│
├── output/
│
├── training/
│   └── ben_affleck/
│       ├── img_1.jpg
│       └── img_2.png
│
├── validation/
│   ├── ben_affleck1.jpg
│   └── michael_jordan1.jpg
│
├── detector.py
├── requirements.txt
└── unknown.jpg


If there are errors such as 

File "/Users/JO/github/ImageRecognition/professor/fromScratchV1/detector.py", line 146, in validate
    recognize_faces(
  File "/Users/JO/github/ImageRecognition/professor/fromScratchV1/detector.py", line 77, in recognize_faces
    input_image = face_recognition.load_image_file(image_location)
  File "/usr/local/Caskroom/miniconda/base/envs/Py39/lib/python3.9/site-packages/face_recognition/api.py", line 86, in load_image_file
    im = PIL.Image.open(file)
  File "/usr/local/Caskroom/miniconda/base/envs/Py39/lib/python3.9/site-packages/PIL/Image.py", line 3532, in open
    raise UnidentifiedImageError(msg)
PIL.UnidentifiedImageError: cannot identify image file '/Users/JO/github/ImageRecognition/professor/fromScratchV1/validation/.DS_Store'

We need to find the solution

# References
