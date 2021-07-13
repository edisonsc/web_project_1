# Learning how to learn project

This website details different ways to learn with each section offering insight into various techniques for better learning.

This website was built based on a design brief and used HTML, CSS, Flexbox, Git and BEM methodology.

## BEM
I created classes using BEM methodology based on the design brief. For the second part of the project, I refactored the code to adhere to BEM file structure.

## Positioning Elements
The design focused on positioning elements accurately according to the brief. I used relative and absolute position for certain elements. The video section was one of the more challenging sections to position. The embedded YouTube videos had to overlap the next section while maintaining a specific margin from the title.

```
.video__iframes {
  display: flex;
  align-items: center;
  justify-content: center;
  position:relative;
  bottom: -50px;
  margin-top: -60px;
  padding:0;
  z-index: 1;
}
```

## Animation
In the second part of the project, I added animations. I created an opacity transition to apply to each link on the site.

I also created a rotation animation used in the the header and kaufman sections.
```
@keyframes rotation {
  from {
    transform: rotate(0deg);
}
to {
  transform: rotate(360deg);
}
}

.rotation {
 animation: rotation 20s infinite linear;
};
```

## Git and GitHub
This project gave me a better understanding of Git and GitHub. I focused on creating clear commits. I was able to revert when I needed to return to a previous commit.

## Future
The next steps for this project include
* Checking the code for cross-compatibility and adding all the necessary vendor prefixes
* Designing a form that allows users to submit a comment
* Adding additional educational content
