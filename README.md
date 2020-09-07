[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]](https://github.com/aadimangla/Sarcasm-Detector/issues)
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
<!--   <a href="">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a> -->

  <h1 align="center">Sarcasm Detector</h1>

  <p align="center">
    <!-- An awesome README template to jumpstart your projects! -->
    <br />
<!--     <a href=""><strong>Explore the docs »</strong></a> -->
    <br />
    <br />
    <!--<a href="">View Demo</a>
    ·
    <a href="">Report Bug</a>
    · -->
    <a href="https://github.com/aadimangla/Sarcasm-Detector/issues">Request Feature</a>
  </p>
</p>


---
<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)

---

<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](images/product.png)

It analyses the text enterd by a user and analyses whether the text is sarcastic or not. Sarcasm, which is both positively funny and negatively nasty, plays an important part in human social interaction. Sarcasm detection is a very narrow research field in NLP, a specific case of sentiment analysis where instead of detecting a sentiment in the whole spectrum, the focus is on sarcasm. Therefore the task of this field is to detect if a given text is sarcastic or not.

Some people could disagree about its purpose, but there is a convention in that people use positive words in order to convey a negative message. Of course, it varies through person to person and is highly dependent on the culture, gender and many other aspects. Americans and Indians for example, perceive sarcasm differently.
Moreover, someone being sarcastic doesn’t mean the other person perceiving it as the speaker intended. This subjectivity will have implications in the performance of DL models.

### Context
Past studies in Sarcasm Detection mostly make use of Twitter datasets collected using hashtag based supervision but such datasets are noisy in terms of labels and language. Furthermore, many tweets are replies to other tweets and detecting sarcasm in these requires the availability of contextual tweets.

To overcome the limitations related to noise in Twitter datasets, this News Headlines dataset for Sarcasm Detection is collected from two news website. TheOnion aims at producing sarcastic versions of current events and we collected all the headlines from News in Brief and News in Photos categories (which are sarcastic). We collect real (and non-sarcastic) news headlines from HuffPost.

This new dataset has following advantages over the existing Twitter datasets:

Since news headlines are written by professionals in a formal manner, there are no spelling mistakes and informal usage. This reduces the sparsity and also increases the chance of finding pre-trained embeddings.

Furthermore, since the sole purpose of TheOnion is to publish sarcastic news, we get high-quality labels with much less noise as compared to Twitter datasets.

Unlike tweets which are replies to other tweets, the news headlines we obtained are self-contained. This would help us in teasing apart the real sarcastic elements.

### Content
Each record consists of three attributes:

is_sarcastic: 1 if the record is sarcastic otherwise 0

headline: the headline of the news article

article_link: link to the original news article. Useful in collecting supplementary data

### Further Details
General statistics of data, instructions on how to read the data in python, and basic exploratory analysis could be found at this GitHub repo. A hybrid NN architecture trained on this dataset can be found at this GitHub repo.

### Inspiration
Can you identify sarcastic sentences? Can you distinguish between fake news and legitimate news?

---

### Built With
This chatbot was build using following frameworks, libraries and softwares.
* [Tensorflow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)
* [Matplotlib](https://matplotlib.org/)

---
<!-- GETTING STARTED -->
## Getting Started

To run this project you need to follow the following steps.

## Getting Started

To run this project you need to follow the following steps.

### Prerequisites

These are the prerequisites you need to build this bot as well as run it.

```sh
cmd:\ pip install tensorflow
cmd:\ pip install keras
```
#### Extra SETUP
- Create conda environment and create project in this environment
- After installing requirements in above Modules LIST
- You need python idle such as Jupyter notebook or spyder
<!-- #### How to Train ?
- ##### To use default Rasa configs
```sh
$ rasa train
```
- ##### To use spacy config pipeline (Fast to train)
```sh
$ rasa train -c spacy_config.yml
```
-->

<!-- #### How to run 
- ##### To run action server
```sh
$ rasa run actions --actions actionserver.actions
```
- ##### To run rasa in debug mode to inspect slot filling and entities ..,
```sh
$ rasa shell --debug
```
- ##### To run rasa in normal shell
```sh
$ rasa shell
```
-->

---

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/aadimangla/Sarcasm-Detector/issues) for a list of proposed features (and known issues).


---
<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

<!-- LICENSE -->


## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2020 © <a href="http://adityamangla.com" target="_blank">Aditya Mangla</a>.

---

<!-- CONTACT -->
## Contact

Aditya Mangla - [@aadimangla](https://twitter.com/aadimangla) - aadimangla@gmail.com - [adityamangla.com](http://www.adityamangla.com/index.html)

Project Link: [https://github.com/aadimangla/Sarcasm-Detector](https://github.com/aadimangla/Sarcasm-Detector)

---

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Tensorflow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)
* [Matplotlib](https://matplotlib.org/)
* [Laurence Moroney](http://www.laurencemoroney.com/)




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/aadimangla/Sarcasm-Detector.svg?style=flat-square
[contributors-url]: https://github.com/aadimangla/Sarcasm-Detector/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/aadimangla/Sarcasm-Detector.svg?style=flat-square
[forks-url]: https://github.com/aadimangla/Sarcasm-Detector/network/members
[stars-shield]: https://img.shields.io/github/stars/aadimangla/Sarcasm-Detector.svg?style=flat-square
[stars-url]: https://github.com/aadimangla/Sarcasm-Detector/stargazers
[issues-shield]: https://img.shields.io/github/issues/aadimangla/Sarcasm-Detector.svg?style=flat-square
[issues-url]: https://github.com/aadimangla/Sarcasm-Detector/issues
[license-shield]: https://img.shields.io/github/license/aadimangla/Sarcasm-Detector.svg?style=flat-square
[license-url]: https://github.com/aadimangla/Sarcasm-Detector/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/aadimangla
[product-screenshot]: images/screenshot.png
