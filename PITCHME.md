## Markdown (.md)

#### Or, what are all these .md files supposed to be?

NOTE:  

so this talk is about markdown

Probably various level of understanding  
Who here:
  - knows about markdown
  - uses markdown
  - fanatically uses markdown

---

### This talk

1. a short explanation
2. a brief history
3. a quick demo
4. Some concise philosophy
5. a few questions?

Note:  

More like a lightning talk. If you already know markdown, stick with me for the philosophy

I hope you'll get out of this:
  - some ideas for how make your life slightly easier
  - how to modify your workflow in support of standardization

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

NOTE:  

We can take a look at some raw markdown, pretty simple

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

show wiki #examples

---

### Online Examples

---

### Software

- VSCode (for side by side viewing)
- Simplenote (for note-taking)
- Many more...

NOTE:  

Show conference talk notes

---

### Some concise philosophy

*Our work as craft*  

*The open source ecosystem*

NOTE:  

Ok, this is really simple, why should I care?  
Nothing about markdown is really technically interesting, why is this a talk
There's some deeper meaning here about:  
- improving how we do our work
- how the open source community works
- how technology ecosystems emerge

---

*For any task, it is important to have lightweight and heavy-weight tools*

NOTE:  

- You should have tools that get out of your way
- For any type of task, you should have simple tools, and heavy-weight tools. Neither is sufficient on its own
  - For code, that's a text editor, like vscode, vim/emacs, vs. an IDE like visual studio
    - editing config files, visual studio optimized for X
  - For writing, that's notepad/text edit vs. word

---

![tools](https://raw.githubusercontent.com/benbp/markdown-presentation/master/screwdrivers.jpg)

NOTE:  

- A broader analogy, screwdriver vs power drill
  - if you need to screw in one thing, you don't reach for your power drill
  - there are more failure modes for a power drill (battery)

---

*Tools have economies of scale*

NOTE:  

- The whole point I'm making is that tools have economies of scale
    - overhead to use the tool vs. time saved by using it
      - (get drill, plug in, etc.), or startup time/CPU/MEM for visual studio/word
    - if all you have for things is the equivalent of power drills, it can take forever to get things done quickly because of:
      - setup
      - context switching
      - failure modes
- how does this relate? 
  - when I'm trying to use writing as a way of thinking, I want as little in the way as possible for getting thoughts down on a page. 
    - For me, I've found that a simple, blank screen and not ever having to stop typing works
    - Others may be different, suggest you try

- Easy to format as you go, easy to export to other views
  - "clean as you cook". You can get thoughts out quickly and not have to fiddle around with formatting too much.
  - as in my talk notes example, if I'm trying to transcribe a talk notes, don't have time to click on "header" etc.
    - but at the same time, I'm left with an output that's well structured
    - I was able to share that in the wiki

- Why important: we want to make writing documentation as easy as possible

---

*Technology thrives when there is standardization and simplicity*

NOTE:  

- Take our documentation for example
  - Within Azure we have lots of docs stored in proprietary programs, OneNote, sharepoint sites, word docs
  - This makes it really hard to make changes to how we do docs, or do engineering
  - One thing we have wanted to do is standardize troubleshooting guides in one place (sovereign), actually ends up being a lot of work

- The open source community, I would argue, isn't really affected by this problem so much
  - even though it's much more decentralized
  - You have just as much variability in doc rendering/hosting: readthedocs, github wiki, etc.
  - But most of them are built on top of common formats like markdown or restructured text
  - many different needs can be served, without creating as much of a fragmentation problem
    - the vscode docs we looked at, if they wanted to host somewhere else, just run a script

---

### Use markdown more, please :)

NOTE:  

- To close, I want to encourage you to use it more
- I think it will benefit you personally, in productivity
- I think it will benefit the company, and the health of our documentation

---

#### These slides written in Markdown (via gitpitch)

NOTE:  

I just wrote my talk, like I was writing an essay  
Didn't have to fiddle around with formatting, etc.

---

### A few questions?

---