


# Introduction

This course is meant to get you started writing scientific manuscripts using LaTeX in Overleaf.

## Motivation

Overleaf is a very useful too for collaborative scientific writing. It has an advantage over other potential collaborative writing options in that it enables for seamless changes in formatting and arrangement of text to allow you to submit to various publication platforms, such as preprint archives or scientific journals. Another advantage of Overleaf is that it is based on using LaTeX which makes it easy to add mathematical formulas to your writing. It also helps you do really complicated formatting and layouts with much more ease than other options and it makes it easy to replicate that complicated formatting/layout again for other papers or other writing products. It is widely used in certain fields like statistics and computer science. Therefore, it can also be useful to know about if you have collaborators in these fields.

## Target Audience  

The course is intended for scientific writers who might be interested in learning how to automate some of their writing formatting/layouts.


<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1bb9ca840c8_0_164.png" title="for indiviudals who: Are unfamiliar with what LaTeX is, but like the idea of more customizable and reproducible formatting  of text in documents. Have heard of LaTeX but don’t know how to use it in practice. Want guidance on collaborating with Overleaf." alt="for indiviudals who: Are unfamiliar with what LaTeX is, but like the idea of more customizable and reproducible formatting  of text in documents. Have heard of LaTeX but don’t know how to use it in practice. Want guidance on collaborating with Overleaf." width="100%" style="display: block; margin: auto;" />


## Curriculum  

The course covers basic information about why LaTeX can be useful, how to get started in overleaf using LaTeX with a template, how to work with a team on overleaf, and what to do when you have problems. 

<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1bb9ca840c8_0_196.png" title="This course will demonstrate how to: 1.Be familiar with what LaTeX is and understand the origins of how it came to be, 2. Understand the benefits of using LaTeX and Overleaf, 3. Get started writing in Overleaf with a template for a scientific manuscript, 4. Add references to a document in Overleaf, 5. Get help if you encounter challenges, 6. Work collaboratively on Overleaf" alt="This course will demonstrate how to: 1.Be familiar with what LaTeX is and understand the origins of how it came to be, 2. Understand the benefits of using LaTeX and Overleaf, 3. Get started writing in Overleaf with a template for a scientific manuscript, 4. Add references to a document in Overleaf, 5. Get help if you encounter challenges, 6. Work collaboratively on Overleaf" width="100%" style="display: block; margin: auto;" />


# LaTeX

You may or may not have heard people talking about [LaTeX](https://www.latex-project.org/about/) (pronounced '/ˈlɑːtɛx/' LAH-tekh or '/ˈleɪtɛx/' LAY-tekh), not to be confused with the the material latex (pronounced '/ˈleɪtɛks/' LAY-tekhs). In this course we will explain what LaTeX is and how it came to be.


<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_0.png" title="LaTex is not latex (the material used for protective gloves and other items)." alt="LaTex is not latex (the material used for protective gloves and other items)." width="100%" style="display: block; margin: auto;" />

## Learning Objectives

<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1bb9ca840c8_0_360.png" title="Learning Objectives: 1. Explain what LaTeX is and how it came to be 2. Understand that writing a document involves two distinct steps 1) writing the content and 2) determining how the content should be displayed, 3. Recognize that applications like microsoft word interactively show you the formatting/arrangement of the document as you write, while markup languages embed how a file should display using specific tags within the text that are later manifested, 4.Begin to understand how markup language tags result in changes to plain text" alt="Learning Objectives: 1. Explain what LaTeX is and how it came to be 2. Understand that writing a document involves two distinct steps 1) writing the content and 2) determining how the content should be displayed, 3. Recognize that applications like microsoft word interactively show you the formatting/arrangement of the document as you write, while markup languages embed how a file should display using specific tags within the text that are later manifested, 4.Begin to understand how markup language tags result in changes to plain text" width="100%" style="display: block; margin: auto;" />

## Document Preparation System

LaTeX is a "document preparation system" according to the LaTeX project [@latex]. It is often used for scientific or technical writing documents, but it can be used for formatting or arranging any type of writing document. This process of determining the final look of a writing product is called [typesetting](https://en.wikipedia.org/wiki/Typesetting). Typesetting determines how text looks and where it is located in a document when it is it's final stage - like when it is rendered or printed. It has to do with fonts, text sizing, line spacing, the arrangement of tables and images, and more.

Although LaTeX has a reputation for being quite tricky, it is very powerful in enabling users to documents with complex and customized text formatting and layouts with much more ease than doing so using systems like Microsoft Word. 


<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_18.png" title="LaTeX allows for fancy document typesetting (meaning formatting and text layout), where as traditional text editors like Microsoft Word requires manual formatting and layout, which often leads to typical looking documents." alt="LaTeX allows for fancy document typesetting (meaning formatting and text layout), where as traditional text editors like Microsoft Word requires manual formatting and layout, which often leads to typical looking documents." width="100%" style="display: block; margin: auto;" />
 



## History

LaTeX was originally released in 1984 by [Leslie Lamport](https://en.wikipedia.org/wiki/Leslie_Lamport), thus the "La" in LaTeX is believed to be for his last name, Lamport. LaTex is one of several programs (but probably the most widely used in academia - in part, because it is free!) that makes it easier to use the [typesetting](https://en.wikipedia.org/wiki/Typesetting) system called TeX.

### TeX

TeX, which is named as an abbreviation for the Greek word [τέχνη (ΤΕΧΝΗ techn](https://en.wikipedia.org/wiki/Techne), which directly translates to art or craft), was developed by [Donald E. Knuth](https://en.wikipedia.org/wiki/Donald_E._Knuth) in the 1970s[@tex_2022]. He developed TeX so he could format the text in his books more to his satisfaction [@tex_2022]. 

Typesetting has origins in how documents used to be printed using manual stamping mechanisms, where someone would provide the contents of the text in writing by hand that would be translated to a version with the intended layout and style for printing.


<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_45.png" title="Historically making printed documents required two steps: 1. Writing the content by hand, 2. Determine the layout and font and arrangement of the text with stamps." alt="Historically making printed documents required two steps: 1. Writing the content by hand, 2. Determine the layout and font and arrangement of the text with stamps." width="100%" style="display: block; margin: auto;" />


Overtime this process got replaced by digital options and eventually resulted in the concept of WYSIWYG (What you see is what you get), where programs like Microsoft Word, let you interactively work with the typesetting of a document as you write the content. 


<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_67.png" title="WYSIWYG - What you see is what you get - the document is displayed like the final product as you write it." alt="WYSIWYG - What you see is what you get - the document is displayed like the final product as you write it." width="100%" style="display: block; margin: auto;" />


In a sense using LaTeX/TeX is kinda taking a step back in time to think about the fact that when you use a program like Microsoft Word, you are essentially giving it two sets of directions simultaneously, one which is the content of the text, and one which is the style and layout of the text. 

With LaTeX we are more aware that we are actually telling the computer how to arrange the text. It also gives us much more control of how we arrange, format, and style the text. If you are really interested in taking a deep dive into understanding how this all came to be, check out this [blog post](https://towardsdatascience.com/why-should-you-learn-latex-or-at-least-give-it-a-try-8d0f3218b8e) by @tirado_reasons_2020 and this [O'Reilly book](https://www.oreilly.com/library/view/making-tex-work/1565920511/) by @walsh_making_1994.

## Process

LaTeX can also be called a [markup language](https://en.wikipedia.org/wiki/Markup_language). These means that certain symbols around plain text can be used to indicate how the plain text should be formatted or displayed. Another example of a markup language is HTML (which actually stands for HyperText Markup Language), which has symbols to indicate how the text should be displayed on webpages. It is often used in computer science to enable humans to read or write a file more easily and for the computer to interpret these files more easily. 

Let's use a simple example of making some text **bold** to describe this. 

**Microsoft Word:** <br>
If we wanted to some text bold in Microsoft Word, we would type the plain text that we want to bold just like the rest of the text. We would then select that text and click some buttons to make the text bold. 

**HTML:**<br>
In HTML we could instead use `<b>` at the beginning of the text we want to bold, and `</b>` at the end to indicate that this text should be in bold when it is rendered into it's final state. 

**LaTeX:**<br>
Just like in HTML, LaTeX also uses text around the actual content text to describe how to produce the final product. In this case, we would indicate that we want bold text using a tag `\textbf` which is abbreviated as `bf` for bold font, with brackets around the text we want to change like so: '\textbf{bold text}'.

<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1babf2134b3_0_153.png" title="A table of the methods just described to bold text to indicate that text around the plain text is used to format the text itself within markup languages." alt="A table of the methods just described to bold text to indicate that text around the plain text is used to format the text itself within markup languages." width="100%" style="display: block; margin: auto;" />
As you can see, LaTex will feel a bit different from writing in Microsoft Word, as we will be using text tags to define how we want the content text to look.

## Benefits of LaTeX

Now that you are a little more clear about what LaTeX is, it might be easier to appreciate it's benefits:

1) Allows you to focus on the content and worry less about formatting (once you have a good template to work with). There are many more specific templates to use for various journals that can be super helpful!
2) Allows for much more complex typesetting/formatting of text. You can customize your documents just the way you would like.
3) Once you have a template you like working with, say for a journal you frequently publish with, it is super easy to format future documents.
4) If you need to change the typesetting/formatting of a document for the requirements of a different journal or preprint archive, you can do it much quicker and with more ease than if you were to do it manually using a text editor like Microsoft Word. 
5) You can add languages with different alphabets or mathematical notation with much more ease than with traditional text editors
6) You can collaborate with people who use LaTeX more easily

<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_77.png" title="Benefits of Using LaTeX: Using a template allows you to focus on the content and not the formatting/layout, Can create very complex documents, Can reproduce style/typesetting of a document easily again, Can easily change the typesetting of an entire document, Can add languages with other alphabets or mathematical notation easily, If you know LaTeX you can collaborate with others who use it!" alt="Benefits of Using LaTeX: Using a template allows you to focus on the content and not the formatting/layout, Can create very complex documents, Can reproduce style/typesetting of a document easily again, Can easily change the typesetting of an entire document, Can add languages with other alphabets or mathematical notation easily, If you know LaTeX you can collaborate with others who use it!" width="100%" style="display: block; margin: auto;" />

## Conclusion

We hope that this chapter has given you some more knowledge about what LaTeX is and how it came to be, as well as the benefits of using it.

In conclusion, here are some of the major take-home messages:

1. Computers actually separate document creation into two tasks, the content  text and arranging and styling that text. Traditional text editors like Microsoft Word show us what the final document will look like as we write it.
2. LaTeX is a document preparation system that makes it easier to use the typesetting system TeX and allows you to create very complicated documents. 
3. Typesetting has to do with all the style, layout, and formatting that a document might need.
4. LaTeX is a markup language and similar to HTML, text tags around the content text can be used to indicate how the document should look when rendered into the final state.
5. LaTex allows you to more easily change how your document is laid out, which can be super beneficial if you need to accommodate different scientific journal requirements. 
6. Although LaTeX is used frequently in computer science, mathematics, statistics, and engineering fields to write technical papers, it can be used for other kinds of documents too!


# Overleaf

Overleaf is an online free LaTeX editor, meaning it helps you write text using LaTeX to determine how your document will look. 

Since LaTeX can be pretty tricky, Overleaf can be super helpful!


<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_91.png" title="LaTeX on it’s own can be quite a challenge, Overleaf makes LaTeX much more approachable." alt="LaTeX on it’s own can be quite a challenge, Overleaf makes LaTeX much more approachable." width="100%" style="display: block; margin: auto;" />
 

## Benefits of Overleaf

There are other LaTeX editors, but Overleaf is a really nice option for a number of reasons:
 
1) It is free! 
1) It's online and requires no installations.
1) It makes it much easier to write using LaTeX.
1) It shows you a preview of your final document.
1) It makes it easy to collaborate with others.
1) There is lots of online support.
1) It can sync with GitHub or Dropbox (if you pay for a paid plan).


## Getting Started

To start, you need to make an account on Overleaf.

To do so, you can go to https://www.overleaf.com/register in your browser.

There are several ways to register:

1. Register with your Google account
2. Register with your ORCID account
3. Register with a different email address
4. Log in with an institution.
    This is worth checking in case your university has a license, as this may provide you with more features. 
    
The free version only allows you to have one collaborator on a project, so collaboration is more limited, however you can still benefit from many of the other features.  Note that students can receive a discount as well.

If possible it might be worth seeing if your institute would be willing to get an organizational license.

<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_137.png" title="There are several ways to register an account on Overleaf." alt="There are several ways to register an account on Overleaf." width="100%" style="display: block; margin: auto;" />
Overleaf is organized with projects. When you create a project, you can start from scratch or start from a template.

<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_142.png" title="New Project Button." alt="New Project Button." width="100%" style="display: block; margin: auto;" />

Let's start with a template to help us better understand the features of Overleaf. We can search through all the templates by clicking on "View All" button of the project menu.  We can also click on the template tab to get to the same template search page.  


You can see that there are many templates to choose from in general!

Let's search for a term, such as `preprint` to see if the templates for preprints. 

You will see that a few of the templates have a blue `official` tag. This is the best option if you find one for the publisher that you are interested in.


<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_168.png" title="The official tag for some templates indicates that the publisher recoginizes and approves of the template as the official tempalte to use for submissions." alt="The official tag for some templates indicates that the publisher recoginizes and approves of the template as the official tempalte to use for submissions." width="100%" style="display: block; margin: auto;" />


We will use a template for arXiv. 

You can go to this link: https://www.overleaf.com/latex/templates/style-and-template-for-preprints-arxiv-bio-arxiv/pkzcrhzcdxmc to start with a particular template to create a manuscript for [arXiv](https://arxiv.org/).


Click the "Open as Template" button to get started. 

https://docs.google.com/presentation/d/1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8/edit#slide=id.g1be15cb26d3_0_174

<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_174.png" title="Click the open as template button to get started with a template." alt="Click the open as template button to get started with a template." width="100%" style="display: block; margin: auto;" />
 
## Viewing documents

So now that we have opened a template, we will start by understanding how we can view our work on Overleaf.


For starters, it easily shows you what the rendered version of your text will look like, taking into account the LaTeX tags that indicate how the text should be arranged and styled.

The default view is to see the raw text (aka source text) on the left and the rendered/compiled version on the right.


<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_106.png" title="The default view in Overleaf is to have raw text shown on the left, while the compiled text is shown on the right." alt="The default view in Overleaf is to have raw text shown on the left, while the compiled text is shown on the right." width="100%" style="display: block; margin: auto;" />


You can also change the view to several other options:

<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_113.png" title="The layout tab alows you to change the view." alt="The layout tab alows you to change the view." width="100%" style="display: block; margin: auto;" />



If you are using the default view and you want to see what the file looks like in the rendered form for the same location as that of the source text of the editor, you can click on the arrow (with the arrowhead facing to the right) in between.

<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_163.png" title="The layout tab alows you to change the view." alt="The layout tab alows you to change the view." width="100%" style="display: block; margin: auto;" />


To do the opposite and go to the location in the source text where you are currently viewing in the rendered text, click the arrow button facing the source text editor.

<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_158.png" title="To update the location of the source text to that of the rendered view, press the arrow facing left towards the source editor." alt="To update the location of the source text to that of the rendered view, press the arrow facing left towards the source editor." width="100%" style="display: block; margin: auto;" />
If you make a change in the source and want to see how it changes the look of the file, you need to press the "Recompile" button. 

<div class = "notice">
It is a good idea to press the "Recompile" button frequently, so that you can identify any errors more easily. If you wait too long to check, then you will have more new changes to look through to try to understand the error.
</div>

<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_188.png" title="To update rendered file with your changes, press the recompile button." alt="To update rendered file with your changes, press the recompile button." width="100%" style="display: block; margin: auto;" />

## Making changes

Now let's try some simple changes to sart getting used to writing with LaTeX. 

First let's change the tilte. We can find the title where the file says "Predict future sale". You can use search the source editor text by clicking on the editor and using the search and find keyboard shortcut (control and the F key). We can type in the "Predict future sale" text to find it. We will find it on line 19 following `\title`.



<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_195.png" title="We can search the source text by click on the editor pane and typing the shortcut keys for find functions (control F)." alt="We can search the source text by click on the editor pane and typing the shortcut keys for find functions (control F)." width="100%" style="display: block; margin: auto;" />

We can search the source text by click on the editor pane and typing the shortcut keys for find functions (control F). We can now replace the text with our own title. Be careful to make sure that the brackets are closed around the replacement text.


<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_208.png" title="Changing the title to New Title." alt="Changing the title to New Title." width="100%" style="display: block; margin: auto;" />

Now we can click the "Recompile button" to see the results.

<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_188.png" title="To update rendered file with your changes, press the recompile button." alt="To update rendered file with your changes, press the recompile button." width="100%" style="display: block; margin: auto;" />

After overleaf is done compiling, you can see that the title has been changed.

<img src="resources/images/01-intro_files/figure-html//1UgGtVn7RsqdQ4pJxDk_dueSyREHcH-uWTNAT27E2mG8_g1be15cb26d3_0_188.png" title="The resulting new title within the document." alt="The resulting new title within the document." width="100%" style="display: block; margin: auto;" />



