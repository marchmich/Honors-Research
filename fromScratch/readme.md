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

# About this material

This is an interesting and practical material inspired and implemented from ref. [1](#references). Notice that we will have everyuthing on this readme, and anyone can take, run and change this material. We will be modifying and changing, but the original work is cited and referenced.

# The folder tree

In the main folder put a unknown.jpg image.

The following shows the tree:
```
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
```

We will not use CNN model at stage, but in the future it will be implemented and tested. It is good idea to run train line several times; to execute this:
1. python detector.py
1. python detector.py
1. python detector.py --help
1. python detector.py --train -m="hog"
1. python detector.py --train -m="hog"
1. python detector.py --train -m="hog"
1. python detector.py --validate
1. python detector.py --test -f test/test_1.jpg
1. python detector.py --test -f test/test_2.jpg
1. python detector.py --test -f test/test_6.jpg

Probably it will have some warnings, but it will show you one recognized person.

<!-- # [References](#references) -->
<a name="references">References</a>

[1] <a href="https://realpython.com/face-recognition-with-python/#step-2-load-training-data-and-train-your-model" target="_blank">Real Python</a>