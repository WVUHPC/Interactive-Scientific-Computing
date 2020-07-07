---
title: "Introduction"
teaching: 30
exercises: 30
questions:
- "What is Interactive Scientific Computing (ISC)?"
- "Why using High Performance Computing (HPC) clusters for ISC?"
objectives:
- "First learning objective. (FIXME)"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---

The purpose of this lesson is to introduce you to Interactive Scientific
Computing using the open on-demand access to Thorny Flat, the latest HPC
cluster on West Virginia University.

Scientific Computing is the use of computers to perform science. The term is very wide in scope and includes doing calculations with computers, but also storing data, cleaning data and producing more data as result of computations. It includes the creation of plots and the use of computers writing scientific papers and research proposals more often as a collaborative effort of several authors. In the case of experimental sciences it also includes the use of computers to control and gather data from equipment.
In modern times, we cannot think about doing science without computers.

However, in this lesson we will use the term Scientific Computing in a more restrictive way. We will use the term for the particular case of doing mostly numerical operations with computers. Like the kind of usage that you probably have when using a Spreadsheet like Excel or a specialize software like Matlab.

The term Interactive Scientific Computing is understood in the common case of using a computer in a similar way as you use a handheld calculator. You enter some input and you expect that input to be processed right away to produce results. The term non-interactive computing refers to the way people typically interact with Supercomputers. Supercomputers are large computing devices usually build as clusters of individual computers. Supercomputers in many cases are used by tens or hundreds of users at the same time. As such, the computations are programmed in advance, the user submit jobs expecting that those jobs start being executed sometime in the future and produce the result that will be analyzed later on.

The idea of using a Supercomputer like a HPC cluster could be intimidating for beginners. However, you could have strong motivations for start using this kind of machines. Your research have scaled to a point where your desktop computer or laptop is not longer capable of managing the task, you need specialized software packages and you do not want to spent time compiling or installing software and you would like to rely on software that is already present on the HPC cluster.

For taking advantage of WVU's High Performance Computing cluster for interactive scientific computing all that you need is a web browser.
On this lesson you will not have to learn Linux commands, you just need to execute one for the purpose of downloading all the materials for the tutorials but beyond that your interaction will take place on a friendly web interface.
You do not have to manually submitting jobs or editing submission scripts, these are tasks very important for HPC but they will delegated for other lesson.

We will be using a tool, a web-based client portal, that hides all that complexity and allow you to start using powerful computers for your research from a web interface, with minimal effort and fast learning curve.

Several technologies are involved here and it is important to understand how those different pieces are interconnected.

Open OnDemand is a web-based client, based on the Ohio Supercomputer Center's proven "OSC OnDemand" platform, that enables HPC centers to install and deploy advanced web and graphical interfaces for their users. HPC resources are accesible from a web browser without the user having to install any special software or plugin.

<a href="{{ page.root }}/fig/OOD-Welcome.png">
  <img style="border:1px solid black;"
  src="{{ page.root }}/fig/OOD-Welcome.png"
  alt="Open OnDemand Welcome Page" height="400"
  />
</a>

Open OnDemand manage the creation of interactive sessions of HPC clusters and the activation of Interactive Apps. At this point, we have enabled two
interactive apps, Jupyter Notebooks and RStudio Server.

## Interactive Apps

Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Uses include: data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and much more. Several languages are supported, but for the purpose of these lesson we will use Jupyter with two languages, Python and Julia

<a href="{{ page.root }}/fig/Jupyter-Welcome.png">
  <img style="border:1px solid black;"
  src="{{ page.root }}/fig/Jupyter-Welcome.png"
  alt="Jupyter Welcome Page" height="400"
  />
</a>

RStudio is an integrated development environment (IDE) for R, a programming language for statistical computing and graphics. RStudio Server is an interactive app that runs as server on the compute node and presents RStudio interface on a web browser.

<a href="{{ page.root }}/fig/RStudio-Welcome.png">
  <img style="border:1px solid black;"
  src="{{ page.root }}/fig/RStudio-Welcome.png"
  alt="RStudio Welcome Page" height="400"
  />
</a>

Those two apps will be used to introduce the fundamentals of three programming languages very popular nowadays for scientific computing.

## Programming Languages


<a href="{{ page.root }}/fig/Logo-Python.png">
  <img
  src="{{ page.root }}/fig/Logo-Python.png"
  alt="Python" height="400"
  />
</a>

<a href="{{ page.root }}/fig/Logo-Julia.png">
  <img
  src="{{ page.root }}/fig/Logo-Julia.png"
  alt="Julia" height="400"
  />
</a>

<a href="{{ page.root }}/fig/Logo-R.png">
  <img
  src="{{ page.root }}/fig/Logo-R.png"
  alt="R" height="400"
  />
</a>



{% include links.md %}
