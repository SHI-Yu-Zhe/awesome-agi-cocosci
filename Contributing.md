# Contribution Guidelines

Please note that this project is released with a [Contributor Code of Conduct](code-of-conduct.md). By participating in this project you agree to abide by its terms.

Please check the hints below to determine what to do in your contribution.

## I am adding a link to a paper or a piece of resource

Please open a new `Pull Request` and append the line(s) to the bottom of the current directory of your target topic/subtopic.

If this is a published paper, the avenue and publish year should be included. If this is a preprint paper, only publish year should be included. If this is a piece of resource, only the maintainer or initiator should be included, as follows:

```

* [Paper Name](publicly-accessible-link-to-the-paper) - ***Journal/Conference/Maintainer/Initiator***, year.

```

And if the paper is retrievable on Google Scholar, the link to the `All Versions` page for the paper should be appended, as follows:

```

[[All Versions](link-to-google-scholar-all-versions-page-for-the-paper)].

```

Links to more resources may be appended, as follows:

```

[[Resource Name](publicly-accessible-link-to-the-paper)].

```

At the last, you should append a short description or summary of the link to the end of the line.

```

* [Paper Name](publicly-accessible-link-to-the-paper) - ***Journal/Conference/Maintainer/Initiator***, year. [[All Versions](link-to-google-scholar-all-versions-page-for-the-paper)]. [[Resource Name](publicly-accessible-link-to-the-paper)]. Discription in natural language.

```

## I am adding a new topic/subtopic or modifying the structure of existing ones

If you are not very sure about your proposal, please feel free to open an `Issue` to share your perspective and have an open discussion in the community!

If you are very confident about your proposal, please open a new `Pull Request`.

First, modify the TOC, as follows:

```

* [First Level Title](#first-level-title)
    * [Second Level Title](#second-level-title)
      * [Third Level Title](#third-level-title)

```

The semantics of the three levels of TOC are:

```

* [Resource Category](#resource-category)
    * [Topic](#topic)
      * [Subtopic](#subtopic)

```

Resource categories are things such as `Courses`, `Papers`, and `Peoples & Books`; topics are things like `Abduction`, `Bayesian Modeling`, and `Concepts`; subtopics are things like `Explanation`, `Scientific Discovery`, and `Rationalization`. In most times resource categories are not modified. 

For example,

```

* [Papers](#papers)
    * [Abduction](#abduction)
      * [Explanation](#explanation)

```

Aftered registering your modification in the TOC, you add or modify the content.

Add resource category title as follows:

```
## Resource Category

```

Add topic title as follows:

```

### Topic

```

Add subtopic title as follows:

```

#### Subtopic

```

Each topic and subtopic must end with a `back-to-top` button, as follows:

```

*[Back to Top](#c)

```

Please note that the `back-to-top` button should not be duplicated if a topic is nested with a subtopic which ends with a `back-to-top` button.

## General Guidelines

Please ensure your pull request adheres to the following guidelines:

- Search previous suggestions before making a new one, as yours may be a duplicate.
- Make an individual pull request for each suggestion.
- Titles should be [capitalized](http://grammar.yourdictionary.com/capitalization/rules-for-capitalization-in-titles.html).
- Keep descriptions short and simple.
- End all descriptions with a full stop/period.
- Order link titles alphabetically within each category.
- Check your spelling and grammar.
- Make sure your text editor is set to remove trailing whitespace.
- Try to make your Pull request and title as descriptive as possible.
- All open source applications should have the [OSS symbol](https://github.com/iCHAIT/awesome-osx/blob/master/media/oss.svg), the primary link for the application should point to the application's website and the OSS symbol should link to the source code. In case the application does not have any website then both the links should point to the source code.
- New categories or improvements to the existing categorization are welcome.

Thank you for your suggestions!
