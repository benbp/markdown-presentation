### This talk

1. a short explanation
2. a brief history
3. a quick demo
4. a concise philosophical rant
5. a few questions?


Note:  


Probably various level of understanding  
Who here:
  - knows about markdown
  - uses markdown
  - fanatically uses markdown

More like a lightning talk. If you already know markdown, stick with me for the rant

I hope you'll get out of this:
  - some ideas for how make your life slightly easier

---

## Markdown (.md)

#### Or, what are all these .md files supposed to be?

---

#### Lightweight Markup Language

*machines can read it, humans can too*


NOTE:  

- It is a LML
- fancy term for both machine readable, human readable

---

Simple syntax for  

**styling** and `formatting` text  

and *conversion* to  

 ![HTML](https://upload.wikimedia.org/wikipedia/commons/1/12/Old_HTML_Logo.svg)  

NOTE:  

- primarily a way to write text that can get converted to html

---

```
Simple syntax for 

**styling** and `formatting` text 

and *conversion* to  

![HTML](https://upload.wikimedia.org/wikipedia/commons/1/12/Old_HTML_Logo.svg)
```

---

*"The overriding design goal for Markdown’s formatting syntax is to make it as readable as possible."*  


*https://daringfireball.net/projects/markdown/*

NOTE:  
- Originally created in 2004 by John Gruber.
- Goal of to be easily readable by humans, compared to writing raw html, etc.
- "publishable as-is", you can publish a raw markdown doc by itself without rendering, still useful

---

### Common uses

- VSTS, Github Pull Request/Issue/Work Item descriptions  
- VSTS, Github Wikis  
- Stack Overflow Questions and Comments  
- READMEs and documentation for many open source projects  
- Software for writing

---

### Standards/implementations

- Markdown.pl *(original perl script)*
- github-flavored markdown *(adds code formatting, etc.)*
- vsts markdown *(adds checklists, work-item relative links)*
- CommonMark *(adds controversy)*
- ...and many more *(by design)*

NOTE:  

Many different markdown syntax additions  
You can extend it for use  
Because it's still readable, even custom syntaxes are portable to other md renderers

---

# DEMO

NOTE:  
- Headers (# and ------)
- Bold, Italic
- Lists
- Inline code
- Code, with syntax (not base spec)
- Links
- Images
- Quotes
- newlines/double space
- HTML <b>test</b>
- tables (but ugly)


---

### Usage online

FILL

also add a github link in here

---

### Software

- Simplenote (for note-taking)
- VSCode (for side by side viewing)

NOTE:  

Show conference talk notes

---

### A concise philosophical rant

NOTE:  

Ok, this is really simple, why should I care?  
Nothing about markdown is really technically interesting  
There's some deeper meaning here about:  
- workflows
- how the open source community works
- how technologies succeed

---

*For any task, it is important to have lightweight and heavy-weight tools*


*Tools have economies of scale*

NOTE:  

*Personal*
- You should have tools that get out of your way
- For any type of task, you should have simple tools, and heavy-weight tools. Neither is sufficient on its own
  - For code, that's a text editor, like vscode, vim/emacs, vs. an IDE like visual studio
  - For writing, that's notepad/text edit vs. word
  - A broader analogy, screwdriver vs power drill
    - tools have economies of scale, time saved vs. time overhead 
      - (get drill, plug in, etc.), or startup time/CPU/MEM for visual studio/word
    - if all you have for things is the equivalent of power drills, it can take forever to get things done quickly because of all the setup
- Key is portability, where notepad or rich text falls short is in how easy it is to format as you go
  - "clean as you cook"
  - as in my talk notes example, if I'm trying to transcribe a talk notes, don't have time to click on "header" etc.
  - but more fundamentally: when I'm trying to use writing as a way of thinking, I want as little in the way as possible for getting thoughts down on a page. 
     - For me, I've found that a simple, blank screen and not ever having to stop typing works
     - Others may be different, suggest you try

*Public*

It is an excellent common denominator,   
portable, separates data source from rendering  
close to code

- Trying to migrate docs, TSGs out of sharepoint, onenote
- Much easier to put docs in source control. Match up with corresponding code commits. View history and take contributions
- Different teams can make different organization and rendering decisions, but the source of truth is the same. Standardization!
- Possibilities open up when you have common, lightweight, open source specifications

---

#### These slides written in Markdown (via gitpitch)

NOTE:  

I just wrote my talk, like I was writing an essay  
Didn't have to fiddle around with formatting, etc.


---

### A few questions

---