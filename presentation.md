[comment]: # (This presentation was made with markdown-slides)
[comment]: # (This is a CommonMark compliant comment. It will not be included in the presentation.)
[comment]: # (Compile this presentation with the command below)
[comment]: # (mdslides presentation.md --include media)

[comment]: # (Set the theme:)
[comment]: # (THEME = black-ish)
[comment]: # (CODE_THEME = base16/zenburn)
[comment]: # (The list of themes is at https://revealjs.com/themes/)
[comment]: # (The list of code themes is at https://highlightjs.org/)

[comment]: # (Pass optional settings to reveal.js:)
[comment]: # (controls: true)
[comment]: # (keyboard: true)
[comment]: # (markdown: { smartypants: true })
[comment]: # (hash: false)
[comment]: # (respondToHashChanges: false)
[comment]: # (slideNumber: true)
[comment]: # (Other settings are documented at https://revealjs.com/config/)

人工智慧 . 資料 . 權利

# AI . Data . Rights

[comment]: # (A comment starting with three or more !!! marks a slide break.)
[comment]: # (!!!)

## 主題 Outline

1. Artificail Intelligence / AI 人工智慧
2. Data (Protection) 資料（保護）
3. Fundamental Rights （基本）權利

[comment]: # (!!!)

人工智慧

# AI

Glossary 名詞解釋

[comment]: # (|||)

[Introduction to AI, ML, DL, Generative AI and NLP and the relationship between them (with a focus on GenAI)](https://medium.com/@amitadhiman3001/introduction-to-ai-ml-dl-generative-ai-and-nlp-and-the-relationship-between-them-with-a-focus-c21ff10bbfad) <!-- .slide: style="float: left; width: 50%; font-size: 0.75em"> -->

- AI 人工智慧
- Machine Learning (ML) 機器學習
- Deep Learning (DL) 深度學習
- Generative AI (GenAI) 生成式AI
- Large Language Model (LLM) 大型語言模型
- Natural Language Processing (NLP) 自然語言處理

[comment]: # (||| data-background-image="https://miro.medium.com/v2/resize:fit:786/format:webp/1*cFPZMybA6mQfyrfvOjeifQ.png" data-background-size="45% auto" data-background-position="right" class="p")

歷史小教室

## Brief Histroy

[comment]: # (|||)

機器學習之迭代

## Iteration of Machine Learning (ML)

`Text` / `Image` / `Video`

| Stage | Stakeholder |
| :--- | :--- |
| 1️⃣ Train | AI service provider, Content creator |
| 2️⃣ Evaluate | AI service provider |
| 3️⃣ Deploy | AI service provider, End user |

- AI service provider: Stability AI / Github / OpenAI
- End user: including content creator

[comment]: # (|||)

生成式AI

## Generative AI

![h:50%](https://learnopencv.com/wp-content/uploads/2020/10/gen_disc_model-1.jpg)

[Generative and Discriminative Models](https://learnopencv.com/generative-and-discriminative-models/)<!-- .element: style="font-size: 0.5em"> -->

[comment]: # (|||)

### ChatGPT

[comment]: # (|||)

### [Stable Diffusion (Version 2)](https://github.com/Stability-AI/generative-models)

Text to image

![h:50%](https://raw.githubusercontent.com/Stability-AI/stablediffusion/main/assets/stable-samples/txt2img/768/merged-0002.png)

[comment]: # (|||)

### (TBD)

Text to video

[comment]: # (|||)

緊張關係

## Tension

(Why) is Generative AI the breaking change?
- Killer application: potential profitability
- Permission for human to view vs. for robot to crawl
- Fair use vs. tokenized training data

[comment]: # (!!!)

資料（保護）

# Data (Protection)

- AI 人工智慧
- Machine Learning (ML) 機器學習
- Deep Learning (DL) 深度學習
- Generative AI (GenAI) 生成式AI
- Large Language Model (LLM) 大型語言模型
- Natural Language Processing (NLP) 自然語言處理

[comment]: # (|||)

## Data

* role in AI era: air supply (along with computing power)
* personal data: def
* infosec

[comment]: # (!!!)

（基本）權利

# (Fundamental) Rights

[comment]: # (|||)

## Right

* def
* example

[comment]: # (|||)

## Privacy 隱私

[comment]: # (!!!)

This is a sample presentation to showcase [markdown-slides](https://gitlab.com/da_doomer/markdown-slides). The source markdown file is [presentation.md](https://gitlab.com/da_doomer/markdown-slides/-/blob/master/example/presentation.md).

[comment]: # (!!!)

Use markdown to harness the power of Reveal.js.

[comment]: # (!!!)

## Lists and math

- Using markdown to write presentations
- Easy lists
- LaTeX math syntax

`$$ J(\theta_0,\theta_1) = \sum_{i=0} $$`

[comment]: # (!!!)

Code syntax highlighting and animations:

```js [1-2|3|4]
let a = 1;
let b = 2;
let c = x => 1 + 2 + x;
c(3);
```

Notice the background color change.

[comment]: # (section attributes for the just-ending slide can be specified:)
[comment]: # (!!! data-background-color="aquamarine")

Use background videos, background pictures and **text formatting**,
everything *without breaking* your markdown files.

[comment]: # (Other background options: https://revealjs.com/backgrounds/)
[comment]: # (!!! data-background-video="media/video.mp4", data-background-video-loop data-background-video-muted data-background-opacity="0.2")

Even speaker notes, accessed through the `S` key on your keyboard.

(You may have to allow pop-up windows and try again.)

Note:
This will only appear in the speaker view! 🤯

[comment]: # (!!!)

## Pictures

![picture of spaghetti](media/image0.gif) <!-- .element: style="height:50vh; max-width:80vw; image-rendering: crisp-edges;" -->

Showcase media including images, videos and animations.

[comment]: # (!!!)

## Animations

- This is an example list
- Just to showcase Reveal.js' animations

[comment]: # (!!! data-auto-animate)

## Animations

- This is an example list
- Just to showcase Reveal.js' animations
- This item will be automatically faded-in

[comment]: # (!!! data-auto-animate)

```js [1-2|3|4]
let a = 1;
let b = 2;
let c = x => 1 + 2 + x;
c(3);
```
<!-- .element: data-id="code" -->

[comment]: # (!!! data-auto-animate)

```js [5]
let a = 1;
let b = 2;
let c = x => 1 + 2 + x;
c(3);
c(5);
```
<!-- .element: data-id="code" -->

Animate code as well <!-- .element: class="fragment" data-fragment-index="1" -->

[comment]: # (!!! data-auto-animate)

Insert Youtube videos.

<iframe width="560" height="315" src="https://www.youtube.com/embed/KPfzRSBzNX4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[comment]: # (!!!)

Insert local videos.

<iframe width="560" height="315" src="media/video.mp4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[comment]: # (!!!)

Download [markdown-slides](https://gitlab.com/da_doomer/markdown-slides)!

[comment]: # (!!!)

A couple more examples follow.

[comment]: # (!!!)

![logo](media/wide.png)

***use markdown to write slides***

Author Name

[comment]: # (!!!)

[comment]: # (!!! data-background-image="media/inkscape.png" data-background-size="contain")

Press down on your keyboard or swipe down.

[comment]: # (|||)

**Vertical slides!**

(thanks [@porvik!](https://gitlab.com/da_doomer/markdown-slides/-/issues/8))

[comment]: # (|||)

As many vertical slides as you like.

[comment]: # (!!!)

Add tables:

| Insert | Tables |
| ------ | ------ |
| A row  | Another|
| text   | more   |

[comment]: # (!!!)

## Vertical separator

----------

Some other text.

[comment]: # (!!!)

You can also use in-line HTML.

<div style="font-size: 1em;">
small
</div>

<div style="font-size: 5em;">
large
</div>
