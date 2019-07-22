# ACH 2019 Manifold Scholarship Workshop

The goal of this hour-long, hands-on segment of our workshop is to give attendees an opportunity to explore Manifold and begin getting comfortable managing content on a Manifold project.

In particular, we'll cover the following tasks:

1. Creating an account and logging in
1. Creating a Manifold project
1. Ingesting texts
1. Customizing the project page
1. Creating resource collections and resources

We'll break up into 4 groups. Each group will create a project on the CUNY Manifold Instance at https://cuny.manifoldapp.org. I'll walk everyone through basic project setup steps, and then cut you loose to setup your own projects.

# 1. Creating an Account and Logging in

Creating a Manifold account is simple. Click on the user icon in the top right corner of the screen. On the login screen, look for the "Need to Sign Up?" link. Click it, and enter your email, name, and password to create an account. Once you sign up, you will be automatically logged in.

_Nota Bene: When you sign up for an account on a Manifold instance, the default "reader" role is assigned to your account. To create projects, you need a "project creator" role. If you already signed up before the workshop, the fine folks at CUNY have already assigned the creator role to your account. If you're just signing up now, the team member working with your group will assign the correct role to your account_

# 2. Creating a Manifold Project

Once you've logged in to an account with project creator permissions, you will see an _enter admin mode_ button in the header. Click it to enter the Manifold backend.

To create a new project, click the "Add a New Project" button. Give your project a title and subtitle, and answer the layout questions. Don't worry if you're not sure about your answers, you can always make adjustments later.

Go ahead and fill out a few fields for your project. Some basic things to do here include:

* Add a publication date
* Setup a "maker" for the project
* Add twitter integration
* Add some metadata

Add a publication date, setupTake a look at the Metadata

# 3. Ingest A Text or Two

Manifold can ingest texts in a variety of formats. To speed things up, we've setup a few suggestions for groups to explore ingestion.

### Suggestion: Ingest a Standard Ebook

The [Standard Ebooks project](https://standardebooks.org) is a volunteer driven, not-for-profit effort to produce a collection of high quality, carefully formatted, accessible, open source, and free public domain ebooks that meet or exceed the quality of commercially produced ebooks.

I've grabbed a few EPUBs in this repository that you can ingest by just entering the URL into Manifold. Alternately, you can select a different book from the [Standard Ebook website](https://standardebooks.org), download the EPUB, and ingest it into Manifold.

* [The Castle of Otranto](https://github.com/ManifoldScholar/ach-workshop/raw/master/texts/epubs/the-castle-of-otranto.epub)
* [The Cosmic Computer](https://github.com/ManifoldScholar/ach-workshop/raw/master/texts/epubs/the-cosmic-computer.epub)
* [The House of Mirth](https://github.com/ManifoldScholar/ach-workshop/raw/master/texts/epubs/the-house-of-mirth.epub)

### Suggestion: Ingest Google Docs from a Manifest

One way of ingesting texts into Manifold is via a manifest file. A manifest is a YAML document that  includes metadata about the text and links to documents that make up the text. Each document can be a Google Doc, a Markdown File, a Word file, or an HTML file. Documents (and the manifest itself) can be ingested from local files uploaded to Manifold, from URLs, or from a combination of remote and local sources.

For this workshop, I've created four manifests that can be ingested. Each manifest represents a text with three parts. Each part is a google doc, which you should feel free to modify!

These manifests can be ingested directly from the source on Github.

* Group #1: [https://raw.githubusercontent.com/ManifoldScholar/ach-workshop/master/texts/manifests/group_1.yml](https://raw.githubusercontent.com/ManifoldScholar/ach-workshop/master/texts/manifests/group_1.yml)
* Group #2: [https://raw.githubusercontent.com/ManifoldScholar/ach-workshop/master/texts/manifests/group_2.yml](https://raw.githubusercontent.com/ManifoldScholar/ach-workshop/master/texts/manifests/group_2.yml)
* Group #3: [https://raw.githubusercontent.com/ManifoldScholar/ach-workshop/master/texts/manifests/group_3.yml](https://raw.githubusercontent.com/ManifoldScholar/ach-workshop/master/texts/manifests/group_3.yml)
* Group #4: [https://raw.githubusercontent.com/ManifoldScholar/ach-workshop/master/texts/manifests/group_4.yml](https://raw.githubusercontent.com/ManifoldScholar/ach-workshop/master/texts/manifests/group_4.yml)

To ingest these manifest, just copy the URL and past it into the Manifold text ingestion interface. Once you've ingested the text, open one or more of the Google Docs referenced in your group's manifest. Make some changes, then reingest the manifest to see the updates in the Manifold Reader.

## 4. Customize the Project Page

In the Manifold Backend, navigate to the _Layout_ section of the project record. Explore the various options in this view, including the following:

* Open the _Description + Images_ interface and add a background, cover image, and a project description.
* Open the _Calls-to-Action_ interface to add links and buttons to the project hero area.
* Open the _Social Links_ interface to add links to your project's social media presences.
* Explore the _Content Blocks_ interface, which allows you to adjust how content is organized on the project page.

## 5. Create a Resource Collection

Let's augment our project with some resources. Create a new resource for your project and give it a thumbnail image.

Go ahead and add a few resources to your project. Explore the different types of resources and see how they render. Depending on how you setup your project, you may need to add a _resources_ content block to the project page.

I've included some sample resources in this repository, which you can download and use on your sample project if you like. You will likely need to right-click on the image and select "Save image as" to save it to your hard drive before uploading it to Manifold.

* [A Photo of a Gothic Castle](https://raw.githubusercontent.com/ManifoldScholar/ach-workshop/master/resources/otranto/castle-arundel.jpg)
* [Another Photo of a Gothic Castle](https://raw.githubusercontent.com/ManifoldScholar/ach-workshop/master/resources/otranto/castle-port-tablot.jpg)
* [An Illustration](https://raw.githubusercontent.com/ManifoldScholar/ach-workshop/master/resources/otranto/isabella.jpg)
* [A photo of the first edition](https://raw.githubusercontent.com/ManifoldScholar/ach-workshop/master/resources/otranto/otranto-text.jpg)

Finally, open your text in the reader and annotate it with a couple resources to get a sense of how we can overlay resources on the base text in Manifold.
