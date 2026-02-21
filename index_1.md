=> What Is This Project?

-A clean, structured, single-page personal profile,Using only semantic HTML

step 1=> my approch ?

i thinked in blocks -

header
main
-about
-skills
-projects
footer

Step 2 — Decide Semantic Meaning

Ask yourself:

What is global navigation? → <header>

What is main content? → <main>

What is a logical content group? → <section>

What is an independent content piece? → <article>

What is contact info? → <footer>

You are training semantic thinking.

Step 3 — Build In Layers

Don’t build everything at once.

Layer approach:

Skeleton (html, head, body)

Header + nav

Main container

Add one section at a time

Footer

Layering builds clarity.

Project Requirements (Clear Target)

Your page must include:

1️⃣ Header

Your name (h1)

Navigation (anchor links to sections)

2️⃣ About Section

h2 heading

Image with alt text

1–2 paragraphs about you

3️⃣ Skills Section

h2

List of skills using ul

4️⃣ Projects Section

h2

At least 2 projects

Each inside <article>

5️⃣ Footer

Email (mailto link)

GitHub link


Common Beginner Mistakes (Avoid These)

Using div everywhere

Skipping alt text

Multiple h1 tags

Messy indentation

Writing everything inside one big section

Forgetting to close tags
<header> → top identity block

<h1> → main heading of entire page

<nav> → semantic navigation container

href="#about" → internal linking system

<header> → top identity block

<h1> → main heading of entire page

<nav> → semantic navigation container

href="#about" → internal linking system

<section> → logical grouping

id="about" → connects to navigation

<h2> → subsection of page (below h1)

<img> → with meaningful alt

<p> → structured description

How id Connects to <a href="#about">

When you write in nav:

<a href="#about">About</a>

The #about means:

“Go to the element whose id is about.”

Now if you have:

<section id="about">

The browser matches:

href="#about"  →  id="about"

The # is just syntax that tells the browser:

“This is an internal fragment identifier.”