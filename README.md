# Relativistic Quantum Waves

This is an educational project I've been working on in my spare time to demystify some of the scarier (very scary imo) topics in quantum mechanics - specifically the Klein-Gordon and Dirac equations.


## What's this even about may you ask?
The goal here is pretty simple: take these intimidating relativistic quantum equations and break them down step-by-step so they actually make sense. I walk through the derivations, explain what we're doing at (almost) every step (to the best of my ability) to hopefully build some intuition along the way.

## Fair warning:
This is a learning project written by someone learning alongside you. **under absolutely NO circumstances should you reference this work in any of your work**. There **are** mistakes in here! That's kind of the point though - this is meant to be a living document that gets better over time.

## This is open source! (with some restrictions)

I really want this to be a collaborative thing. If you spot errors (you probably will), have better explanations, or want to add content - **please contribute!** Seriously, PRs are more than welcome, they're encouraged. Let's make this resource better together. **View the Contributing** section to see specifics before creating a PR!


## Building

To compile the document:

```bash
pdflatex relativistic-quantum-waves.tex
```

You may need to run it twice to get the table of contents and references correct.


## Contributing

Found a mistake? Have a better way to explain something? Want to add content? Here's how to contribute:

*What I'm looking for*:

- **Corrections** - Math errors, typos, conceptual mistakes.
- **Clarifications** - Better explanations or additional context.
- **Extensions** - More derivations, examples, or related topics.

**Important guidelines**

1. **Use LaTeX** This document is created with LaTeX, keep it that way. any PR with partial updates in other languages (e.g., Typst) will **not** be accepted. Only complete translations would be considered.

2. **Use the templates!** The templates/ directory has all the custom LaTeX styling, macros, and preambles I've used in this project. Please use these to keep the document consistent:
     - templates/preamble.tex - Main document setup
     - templates/macros.tex - Custom commands and shortcuts
     - templates/letterfonts.tex - Font configuration
Any PR that tries to use custom styling and does not use the ones provided in the templates/ folder will not be merged.

3. **Respect the formatting** There are certain ways the LaTeX document should be formatted. Please use built-in LaTeX math environments and restrain yourself from making your own hacky solutions. **Also**, do **NOT** use the \[ \] environment, for single equations use \begin{equation} \end{equation} and the equivalent for align.

4. **Keep it clean!** Don't commit LaTeX build artifacts. Make sure your .gitignore includes:
    - *.aux, *.log, *.toc, *.fdb_latexmk, *.fls, *.synctex.gz, *.bbl, *.blg, etc.

5. **Stay casual** - The tone is meant to be approachable and conversational, not overly formal or textbook-y.


## License

Feel free to use this for learning, teaching (not recommended, but shout me out if you do), or whatever. If you find it helpful, I've succeeded in my goal.
