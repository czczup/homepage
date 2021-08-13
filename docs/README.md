---
pageClass: home-page
# some data for the components

name: Zhe Chen (陈喆)
profile: /profile.jpg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/czczup
  - title: email
    icon: "/icons/email.svg"
    link: 'mailto:wztxy89[at]163.com'
    
cv: /pdf/cv.pdf
bio: M.S. Student at Nanjing University
email: chenzhe98@smail.nju.edu.cn
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

I am an M.S. student in Department of Computer Science and Technology, Nanjing University (NJU) since 2020, supervised by [Prof. Tong Lu](https://cs.nju.edu.cn/lutong/). 
I received my bachelor degree from School of Information and Electronic Engineering, Zhejiang University of Science and Technology (ZUST) in 2020.

My research interests are computer vision and deep learning. I did some works about semantic segmentation, object detection, and neural style transfer.

## News
- [2021-03-23] Code of URST is released at [here](https://github.com/czczup/URST).
- [2020-12-21] Our team wins the champion of [NAIC 2020 Remote Sensing Semantic Segmentation Task (1,000,000 RMB bonus)](https://cs.nju.edu.cn/b8/d5/c1654a506069/page.htm).
- [2020-09-01] Attended Nanjing University.
- [2020-05-12] [SiameseCCR](https://ietresearch.onlinelibrary.wiley.com/doi/epdf/10.1049/iet-ipr.2019.0618) is accepted by IET Image Processing.


## Education & Experiences

- **Nanjing University, Nanjing, China** <br/>
Sept 2020 - Present

- **Zhejiang University of Science and Technology, Zhejiang, China** <br/>
Sept 2016 - June 2020
  

## Publications


[→ Full list](/projects/)

<ProjectCard image="/projects/urst.jpg" hideBorder=true>

  **Towards Ultra-Resolution Neural Style Transfer via Thumbnail Instance Normalization**

  **Zhe Chen**, Wenhai Wang, Enze Xie, Tong Lu*, Ping Luo

  Technical Report, 2021

  Introduction: URST is a versatile framework for ultra-high resolution style transfer under limited memory resources.

  [[Paper](https://arxiv.org/pdf/2103.11784.pdf)] [[Code](https://github.com/czczup/URST)] [[BibTex](https://scholar.googleusercontent.com/scholar.bib?q=info:zSy0_gpYt8kJ:scholar.google.com/&output=citation&scisdr=CgWsKTJqEI--3pFKW-0:AAGBfm0AAAAAYRZMQ-2DcnfFNGEUcu-921CU2wM94yAh&scisig=AAGBfm0AAAAAYRZMQ9HRcai2t7C_-IJwTRtcfi0nGhM3&scisf=4&ct=citation&cd=-1&hl=en)]

</ProjectCard>


<ProjectCard image="/projects/siamese_ccr.jpg" hideBorder=true>

  **SiameseCCR: A Novel Method for One-shot and Few-shot Chinese CAPTCHA Recognition using Deep Siamese Network**

  **Zhe Chen**, Weifeng Ma*, Nanfan Xu, Caoting Ji, Yulai Zhang

  IET Image Processing, 2020 (SCI Impact Factor: 2.373)

  Introduction: We proposed a Siamese network-based method for one-shot and few-shot Chinese CAPTCHA Recognition.
  
  [[Paper](https://ietresearch.onlinelibrary.wiley.com/doi/epdf/10.1049/iet-ipr.2019.0618)] [[Code](https://github.com/czczup/SiameseCCR)] [[BibTex](https://scholar.googleusercontent.com/scholar.bib?q=info:hVCGrrz8xRsJ:scholar.google.com/&output=citation&scisdr=CgWsKTJqEI--3pE3THQ:AAGBfm0AAAAAYRYxVHTzAjddCP8F0tyu_UdKM-B0A000&scisig=AAGBfm0AAAAAYRYxVP9qCL6gz6H73X7DO9RR3GsU2o6v&scisf=4&ct=citation&cd=-1&hl=en)]

</ProjectCard>


## Awards & Honors

### Contests

- The 2nd National Artificial Intelligence Challenge (NAIC), Remote Sensing Semantic Segmentation Task, 2020, [**1st Place**](https://cs.nju.edu.cn/b8/d5/c1654a506069/page.htm) **(1,000,000 RMB Bonus)**.
- The 2nd China Gaofen Cup Beautiful Countryside Competition, Remote Sensing Crop Classification Task, 2019, [**3rd Prize**](https://yjs.zust.edu.cn/info/1035/2176.htm) **(5,000 RMB Bonus)**.
- The 9th National Undergraduate E-commerce "Innovation, Creativity and Entrepreneurship" Challenge, Zhejiang Division, 2019, [**1rd Prize**](https://sem.zust.edu.cn/info/1103/1713.htm).
- The 9nd National Undergraduate Service Outsourcing Competition, Captcha Recognition Task, 2018, **2rd Prize**.
### Honors
- Outstanding Graduate of Zhejiang Province
- Zhejiang Provincial Government Scholarship

<!-- Custom style for this page -->

<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 120px
        max-height 120px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px

</style>
