# Servicenow-Service-Portal-Roadmap
This repository is expected to be a guideline for achieving a beginner level proficiency in using Service Portal in Servicenow.


## What is it?

This is a simple study plan for going from new joinees or team members to be able to build basic Service portal Apps in Servicenow and to ramp up their servicenow capabilities.

This is meant for **new engineers** or those who want to revise their service portal knowledge. If you are expert or have previous service portal development experience most of the content will seem very simple or easy to you.

This started out an assignment to train team members not too proficient in UI on being able to build basic apps so it is just one of the roadmaps. Mastering Service portal will require a lot more practice. I am hoping to keep this document alive and keep updating as more resources keep adding for more advanced level. For now the focus is for beginner level only.

As I won't be assessing anyone on the completion or work assigned. The course or road map expects certain of the mentioned resources to be completed by self study. You are expected to mark them as complete once you have been through the resource.
This would be a self assessment and should help you give confidence in building basic apps on service portal.

---

## Table of Contents

- [What is it?](#what-is-it)
- [How to use it](#how-to-use-it)
- [Book List](#book-list)
- [Prerequisite Knowledge](#prerequisite-knowledge)

## How to use it

<details>
<summary>How to use it</summary>

Everything below is an outline, and you should tackle the items in order from top to bottom.

I'm using Github's special markdown flavor, including tasks lists to check progress.

**Create a new branch so you can check items like this, just put an x in the brackets: [x]**

Fork this repo, checkout to your system , create a branch to keep progress.

    Mark all boxes with X after you completed your changes

`git add . `

`git commit -m "Marked x" `

`git push --force `

</details>

## Prerequisite Knowledge
  - One has to be proficient in ServiceNow (Admin + Dev)
  - Basic Knowledge of Javascript (ES 5 is sufficient), CSS + SASS (SCSS as widget editor shows) (Bootstrap preloaded), HTML
  - AngularJS knowledge

## Book List - This is optional
- [ ] [Mastering ServiceNow](https://www.amazon.in/Mastering-ServiceNow-Martin-Wood/dp/1782174214/ref=sr_1_1?ie=UTF8&qid=1544426871&sr=8-1)
    - One has to be proficient in ServiceNow to start build rich UI experiences in Service portal
- [ ] [Professional AngularJS](https://www.amazon.in/Professional-AngularJS-WROX-Valeri-Karpov/dp/8126556439/ref=sr_1_22?ie=UTF8&qid=1544427235&sr=8-22&keywords=angular)
    - Service portal is basically a wrapper around AngularJS to help build SPA apps in servicenow

## Assignment Resources - Mandatory to complete beginner level.
  - [ ] [AngularJS Fundamentals In 60-ish Minutes](https://www.youtube.com/watch?v=i9MHigUZKEM)
    - Although it is quite old, it gives a good introduction to AngularJS in simple language. A lot has changed since then, especially routing and how controllers are added to modules, but such changes won't have much impact on your service portal capabilities. So it is recommended you learn more on your own understand angular better.
  - [ ] [PhoneCat Tutorial App](https://docs.angularjs.org/tutorial/)
    - Please build this basic app to get a basic confidence in making apps in AngularJS
  - [ ] [John Papa Style guide](https://github.com/johnpapa/angular-styleguide/blob/master/a1/README.md)
    - We follow the above style guide in our project mostly. This is endorsed by the angular team itself.
  - [ ] [Service Portal | Anatomy of a Widget](https://www.youtube.com/watch?v=MllpUpcl6TI)
    - This will help you understand the Widget lifecycle. This is most essential information when it comes to widget development.
  - [ ] [Assignment]
    - You need to explore, service portal forms and links in navigation. Study about most of the topics in documentation and community and have basic level knowledge of terms such as portal, url suffix, theme, default pages, logo, branding editor etc
    - Build a basic app by creating a page and widget. Build the phone cat app again, and instead of routing as mentioned in the tutorial, communicate within widget in servicenow way.

## Video resources -This is optional
  - [ ] [TechNow Ep 28 | Service Portal - Part 1 of 2](https://www.youtube.com/watch?v=wzCGZ5Mq5iU)
  - [ ] [TechNow Ep 29 | Service Portal - Part 2 of 2](https://www.youtube.com/watch?v=HtOpbk_00Qw)
  - [ ] [ServiceNow Community](https://community.servicenow.com/community)
    - There are excellent resources in ServiceNow Community, and our technical evangelist do a great job. I encourage you to explore these out.
