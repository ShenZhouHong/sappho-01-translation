# Translation of Sappho Fragment 1: Ode to Aphrodite
2018 Freshmen Language translation of Sappho fragment 1. Glossed and translated by Shen Zhou Hong `<shong@sjc.edu>`

## Original Aeolic Greek
> ποικιλόθρον' ἀθανάτ Ἀφρόδιτα,
> παῖ Δίος δολόπλοκε, λίσσομαί σε,
> μή μ' ἄσαισι μηδ' ὀνίαισι δάμνα,
>      πότνια, θῦμον,
>
> ἀλλὰ τυίδ' ἔλθ', αἴ ποτα κἀτέρωτα
> τὰς ἔμας αὔδας ἀίοισα πήλοι
> ἔκλυες, πάτρος δὲ δόμον λίποισα
>      χρύσιον ἦλθες
>
> ἄρμ' ὐπασδεύξαισα· κάλοι δέ σ' ἆγον
> ὤκεες στροῦθοι περὶ γᾶς μελαίνας
> πύκνα δίννεντες πτέρ' ἀπ' ὠράνωἴθε-
>      ρος διὰ μέσσω·
>
> αἶψα δ' ἐξίκοντο· σὺ δ', ὦ μάκαιρα,
> μειδιαίσαισ' ἀθανάτωι προσώπωι
> ἤρε' ὄττι δηὖτε πέπονθα κὤττι
>      δηὖτε κάλημμι
>
> κὤττι μοι μάλιστα θέλω γένεσθαι
> μαινόλαι θύμωι· τίνα δηὖτε πείθω
> μαισ' ἄγην ἐς σὰν φιλότατα; τίς σ', ὦ
>      Ψά]πφ', ἀδικήει;
>
> καὶ γὰρ αἰ φεύγει, ταχέως διώξει,
> αἰ δὲ δῶρα μὴ δέκετ', ἀλλὰ δώσει,
> αἰ δὲ μὴ φίλει, ταχέως φιλήσει
>      κωὐκ ἐθέλοισα.
>
> ἔλθε μοι καὶ νῦν, χαλέπαν δὲ λῦσον
> ἐκ μερίμναν, ὄσσα δέ μοι τέλεσσαι
> θῦμος ἰμέρρει, τέλεσον, σὺ δ' αὔτα
>      σύμμαχος ἔσσο.

--- Sappho Fragment 1, Ode to Aphrodite

## Interlinear Gloss
### Stanza 1
> ποικιλόθρον' ἀθανάτ Ἀφρόδιτα,
> παῖ Δίος δολόπλοκε, λίσσομαί σε,
> μή μ' ἄσαισι μηδ' ὀνίαισι δάμνα,
>      πότνια, θῦμον,

### Stanza 2
> ἀλλὰ τυίδ' ἔλθ', αἴ ποτα κἀτέρωτα
> τὰς ἔμας αὔδας ἀίοισα πήλοι
> ἔκλυες, πάτρος δὲ δόμον λίποισα
>      χρύσιον ἦλθες

### Stanza 3
> ἄρμ' ὐπασδεύξαισα· κάλοι δέ σ' ἆγον
> ὤκεες στροῦθοι περὶ γᾶς μελαίνας
> πύκνα δίννεντες πτέρ' ἀπ' ὠράνωἴθε-
>      ρος διὰ μέσσω·

### Stanza 4
> αἶψα δ' ἐξίκοντο· σὺ δ', ὦ μάκαιρα,
> μειδιαίσαισ' ἀθανάτωι προσώπωι
> ἤρε' ὄττι δηὖτε πέπονθα κὤττι
>      δηὖτε κάλημμι

### Stanza 5
> κὤττι μοι μάλιστα θέλω γένεσθαι
> μαινόλαι θύμωι· τίνα δηὖτε πείθω
> μαισ' ἄγην ἐς σὰν φιλότατα; τίς σ', ὦ
>      Ψά]πφ', ἀδικήει;

### Stanza 6
> καὶ γὰρ αἰ φεύγει, ταχέως διώξει,
> αἰ δὲ δῶρα μὴ δέκετ', ἀλλὰ δώσει,
> αἰ δὲ μὴ φίλει, ταχέως φιλήσει
>      κωὐκ ἐθέλοισα.

### Stanza 7
> ἔλθε μοι καὶ νῦν, χαλέπαν δὲ λῦσον
> ἐκ μερίμναν, ὄσσα δέ μοι τέλεσσαι
> θῦμος ἰμέρρει, τέλεσον, σὺ δ' αὔτα
>      σύμμαχος ἔσσο.

## Technical Information
### Compiling document
In order to compile latex source files, run `make` in the terminal:
```
cd latex
make
make clean
```

Note: for any partial compiles where compilation fails at a certain point, you
should run `make clean` followed by make again. Trying to run make after a
failed compile would result in additional errors.

### Dependencies
This template uses a makefile to compile the latex source files. The makefile
uses `latexmk`, which runs latex the correct number of times. This is because
due to the presense of figures, tables, and biblatex databases, latex needs to
be called multiple times in some cases. Latexmk should be included in your
latex installation, but if it is now, you may download it here:

* http://personal.psu.edu/jcc8//software/latexmk-jcc/

Additionally, this template uses XeLaTeX by default, as it allows the inclusion
of unicode characters in the latex source files. If XeLaTeX is not installed, or
plain LaTeX is required, simply alter the `makefile` at the appropriate call:

```
# MAIN LATEXMK RULE
$(source_name).pdf: $(source_name).tex
  ...
	latexmk -pdf -xelatex -use-make $<
```

XeLaTeX allows one to use foreign characters like ü or æ natively in the latex
source files, though. So it's probably a good idea to install XeLaTeX:

* http://xetex.sourceforge.net/

### Related documentation
For an overview of how to populate biblatex `citations.bib` files, visit the
biblatex-mla manual at CTAN.

* https://www.ctan.org/pkg/biblatex-mla

### GPLv3 License
The raw template itself is licensed under the terms of the GPL (version 3). A
full copy of the license is attached in `LICENSE.md`. Naturally, any works
that you create using this template (i.e. any actual essays you write using
it) will be your own intellectual property. The GPLv3 license only applies to
any derivative templates.
