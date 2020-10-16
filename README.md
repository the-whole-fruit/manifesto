<p align="left">
    <a href="https://github.com/the-whole-fruit/manifesto/blob/master/LICENSE.md">
        <img src="https://img.shields.io/badge/license-MIT-brightgreen" alt="Contributors" /></a>
    <a href="https://github.com/the-whole-fruit/manifesto/releases">
        <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/the-whole-fruit/manifesto"></a>
    <a href="https://github.com/the-whole-fruit/manifesto/contributors">
        <img src="https://img.shields.io/github/contributors/the-whole-fruit/manifesto" alt="Contributors" /></a>
    <a href="https://github.com/the-whole-fruit/manifesto">
        <img alt="GitHub stars" src="https://img.shields.io/github/stars/the-whole-fruit/manifesto"></a>
    <a href="https://github.com/the-whole-fruit/manifesto">
        <img src="https://img.shields.io/badge/writing%20standard-the%20whole%20fruit-brightgreen"
            alt="We believe writing good code is not only about writing good code. It’s also about the words around it. We aims to deliver both: code and words."> 
    </a>
    <a href="https://twitter.com/intent/follow?screen_name=writingfordevs">
        <img alt="Twitter URL" src="https://img.shields.io/twitter/url?url=http%3A%2F%2Ftwitter.com%2Fwritingfordevs"></a>
</p>

# The Whole Fruit Manifesto 

We believe that “writing good code” is not only about “writing good code”. Sure, the code is the kernel. But around it, or about it, the software developer has to write a lot of words. 

- Technical Documentation
- Code Comments
- Commits, Pull Requests
- Tasks
- Emails

We believe that good code can be made bad by improper use of words around it. Therefore, a software developer who strives to deliver good code needs to also communicate efficiently in writing. 

Such is the whole fruit of a developer’s labor, kernel and all.

<a href="#how-to-adopt"><img alt="Adopt the Manifesto" src="https://img.shields.io/badge/-adopt%20the%20manifesto-brightgreen"></a>

[Guidelines for Writing Effectively](#guidelines-for-writing-effectively) | [How to Adopt](#how-to-adopt) | [How to Contribute](#how-to-contribute) | [About](#about) | [License](#license)

<br>

## Guidelines for Writing Effectively

The **ONE = MOR framework** was created to help software developers communicate better in writing. So feel free to link to this section in your `Contributing.md`. 

We believe that even reading this section _just once_ will result in better contributions and better communication.

![photo_2020-09-15 14 14 49](https://user-images.githubusercontent.com/1032474/93248597-0e78b680-f75e-11ea-842f-823820ccac03.jpeg)

### Step 1. ORGANIZE the information to fit your goals and readers (the result is your _blueprint_)
- **Mob** - know your readers
    - The readers of your PR are software developers, just like you. What compels them to read your PR? If you’re contributing to an open source project, they’ve probably put in hundreds or thousands of hours of their life into a project that makes no money, or very little money. Most likely they are busy, have full-time jobs, spouses, children, pets. But, just like you, they have a passion for building stuff, and they love that their work actually helps people. If you're contributing to your company’s project, then the developer who reviews the PR has to do it because it’s her job. Either way, you want to make their life as easy as possible and the task as pleasant as possible. Don’t treat them like they don’t have a choice but to review your code. Because, _just like you_, they have _a passion for building stuff_, and they love that _their work actually helps people_. That's why they started this. That's why they keep doing it.
- **Mission** - determine your objectives
    - To get your PR approved. From the first try, if possible.
    - To lend a helping hand to someone who’s already helped you, by creating and maintaining a project.
- **Message** - find what will make your readers act for your mission
    - In order for the maintainers to merge your PR, they’ll need to:
        - Easily understand what problem you’re fixing.
        - Agree that the problem is worth fixing.
        - Easily merge your work into the existing code base.
    - Most of the time, the message that should come across is that:
        - Your code contributes something important.
        - Your code is easy to read and well-commented.
        - Your code works and is well-tested.
- **Medium** - select the best communication channel to use
    - For small contributions, go ahead and create a PR.
    - For bigger contributions, it’s better to create an Issue first, to make sure the problem you discovered is worth working on; don’t start working, before you know your work will be merged.
- **Mood** - think about the tone that will make your message more convincing
    - Try to be informal, but not impolite. You’re talking to a colleague.
    - Jokes are welcome and appreciated. Especially good ones.
    - But most importantly, be direct. You are improving something specific.
    - Bonus tip: One or two emojis or GIFs can easily lighten the mood.
- **Mould** - Decide the structure that will carry your message home
    - The Issue or PR you’re opening should already include some text and headlines, to make sure your message is well structured. Try to answer all existing headlines. If needed, add new headlines, but don’t delete the existing ones, they’re there for a reason.
    - If there’s no Issue template, here’s [a good structure for a Bug Report](https://github.com/the-whole-fruit/manifesto/blob/master/.github/ISSUE_TEMPLATE/bug_report.md).
    - If there’s no PR template, here’s [a good structure for a PR description](https://github.com/the-whole-fruit/manifesto/blob/master/.github/ISSUE_TEMPLATE/pull_request.md).

### Step 2. NOTE everything down following the blueprint (the result is your _first draft_)
- Only clear Subjects
    - [ ] Sentences start with their subject (X did Y);
    - [ ] One sentence, one subject;
    - [ ] The subject is a person or a concrete object;
    - [ ] The subject is clear (if unclear, properly explain the subject and its role);
    - For example: Rather than saying _"404 error on moderation"_, you should say something like _"When the users click the Moderate button they get a 404 Error."_ - when the subject is a person, it reads like a story - which is good; When the subject is the first thing in the sentence, you set a clear _context_.
- Only clear Actions
    - [ ] The action is concrete and easy to understand;
    - [ ] The action comes right after the subject (X did Y);
    - [ ] Use verbs instead of subjects whenever possible;
    - For example: _"Authentication throws error 500 when token is missing"_ is more difficult to understand than _"User tries to authenticate without a token, but sees a 500 error page"_;
- Only the right Style
    - [ ] Use the same words you would if you were speaking them;
    - [ ] Use simple words, that anybody can understand;
    - [ ] Avoid abstract words. Avoid buzzwords.
    - [ ] Write about what can be experienced, felt.
    - [ ] Be direct and concrete.
    - [ ] Used examples, metaphors or comparisons where complicated.
    - [ ] Avoided passive voice.
    - [ ] Used the right words for the amount of certainty you have about the subject at hand.
    - [ ] Avoid jargon.
    - [ ] Used bullet points instead of enumerations.
    - [ ] Highlight/underline/bolden the key ideas or words.
    - [ ] Explain the acronyms/abbreviations if any.
    - [ ] Make sure the text is easy to read and has a good flow.
- Only the right Length
    - [ ] Keep the message as short as possible, without missing crucial information.
    - [ ] At most, sentences should have 20-25 words each.
    - [ ] Break down long sentences into short ones - one idea per sentence.
    - [ ] Alternate long sentences with short ones.

### Step 3. EDIT it to make sure it does what it needs to do (the result is your _final text_)
- Read once for sense and structure (the result is your _second draft_)
- Read once to make sure it sounds good (the result is your _third draft_)
- Read once for grammar (the result is your _final draft_)

<br>

## How to Adopt

#### (I) Add a section about The Whole Fruit Manifesto and Guidelines for Writing Effectively to your CONTRIBUTING.md

Remember: One small block of text to add to your CONTRIBUTING.md file, one giant leap in software quality for your project.

Github, Bitbucket and Gitlab use this file to show developers a few guidelines before they submit a PR. We think it's a perfect place to also talk about the guidelines your community follows when communicating in writing. If you adhere to The Whole Fruit Manifesto feel free to copy or link directly to its Writing Guideline. If you don’t have any idea how to structure your `CONTRIBUTING.md` file [here is a template](https://github.com/the-whole-fruit/manifesto/blob/master/.github/CONTRIBUTING.md) that we think is a good start.


#### (II) Include a shield in your project

Shields (aka badges) usually let people know about your project status, standards and permissions. It's also a perfect way to communicate that your project abides by The Whole Fruit Manifesto standard.

You can add the shield below at the top of your README.md using one of the code options under it. 

[![We believe writing good code is not only about writing good code. It’s also about the words around it. We aims to deliver both: code and words.](https://img.shields.io/badge/writing%20standard-the%20whole%20fruit-brightgreen)](https://github.com/the-whole-fruit/manifesto)

```js
[![We believe writing good code is not only about writing good code. It’s also about the words around it. We aims to deliver both: code and words.](https://img.shields.io/badge/writing%20standard-the%20whole%20fruit-brightgreen)](https://github.com/the-whole-fruit/manifesto)

// or

[<img src="https://img.shields.io/badge/writing%20standard-the%20whole%20fruit-brightgreen" title="We believe writing good code is not only about writing good code. It’s also about the words around it. We aims to deliver both: code and words.">](https://github.com/the-whole-fruit/manifesto)
```

Alternatively, you can use [shields.io](https://shields.io) to make a shield that's a better fit for your project. Make sure you point it to `https://github.com/the-whole-fruit/manifesto`

#### (III) Sign the manifesto

If you're the owner of an open-source project or organisation, you can add your name to our SIGNATORIES.md file. This will:
- help you _publicly_ commit to follow The Whole Fruit Manifesto standard in your software projects;
- help other people understand the importance of our cause: _better writing makes for better software_;

<a href="https://github.com/the-whole-fruit/manifesto/blob/master/SIGNATORIES.md"><img alt="Sign Manifesto" src="https://img.shields.io/badge/manifesto-sign%20now-brightgreen"></a>

<br>

## How to Contribute

See our [`CONTRIBUTING.md`](https://github.com/the-whole-fruit/manifesto/blob/master/CONTRIBUTING.md), of course.

<br>

## About

**Why?** This project is the result of many years of added frustration. Time and time again we've seen _great_ ideas, projects and developers who, due to poor communication, either put a ceiling on their success or turn a wonderful experience into a frustrating one. We've grown so frustrated with this, that we felt compelled to do something about it. We felt the urge to actually promote _the importance of good writing_ in web development.

**Who are we?** A [software developer](https://tabacitu.ro) and [a copywriter](https://ro.linkedin.com/in/andreiiordache). This is an unlikely alliance, we know. But it's probably the best mix for starting a project like this.

**What's the plan?** Ideally, to start a movement. To spread the word, little by little, that _words matter_ and that _it's not difficult_ to get decent at writing (definitely not more difficult than learning a new programming language). We want to see fewer and fewer projects that are _hurt_ by their communication. And long-term, we want to completely eliminate the stereotype that developers are bad at communication. In fact, we belive it could become the exact opposite!

**What's the catch?** No catch, really - we're doing this because we believe it needs to be done. In the spirit of full disclosure, though, we are [writing a book](https://writingfordevs.com) on this topic. A half-a-page `contributing.md` section can get you from _bad_ to _decent_. A book can probably take you from _decent_ to _good_. The book is mostly written - we've tried to cram all our writing experience inside it. But it's still a long way from launching, because now we want _other developers_ to tell us what _they've learnt_ makes better writing in software. We're not sure what form this feedback will take, but if this is a problem you've had to fix yourself, and feel you have something to say about this, please reach out to us at <a href="mailto:contact@writingfordevs.com">contact@writingfordevs.com</a>. We might even start an interview series, a podcast, something like that, where we try to learn as much as possible from others, and share that information with everyone.

<br>

## License

The MIT License (MIT). Please see our [License File](https://github.com/the-whole-fruit/manifesto/blob/master/LICENSE.md) for more information.
