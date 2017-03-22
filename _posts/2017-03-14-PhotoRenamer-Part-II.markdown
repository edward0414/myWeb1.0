---
layout: post
title:  "PhotoRenamer Part II"
date:   2017-03-14 16:12:43
tags: Java, JComponent, PhotoRenamer
---

Continue from part I of PhotoRenamer.

Now, I needed to think of a design that is straight-forward and comfortable for the users. I decided to create multiple frames that allow users to choose directory, then images within the directory, and then tags to add.

The whole GUI is made of built-in JComponent of Java class. I created a lot of JTextField for all the input and a JButton for the resulting output. Then, I appended all the JTextField and JButton into a JPanel and then to a JFrame. Eventually, I created the scrollable JPanel to store the result and set the JFrame to visible.

Work in Progress...

You can check out the code on my [github page].

[github page]: https://github.com/edward0414/PhotoRenamer
