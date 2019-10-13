---
title: 'LD(1)'
---

  ------- ------------------------- -------
  LD(1)   General Commands Manual   LD(1)
  ------- ------------------------- -------

::: {.manual-text}
[NAME](#NAME){.permalink} {#NAME .Sh title="Sh"}
=========================

`ld`{.Nm title="Nm"} ---

::: {.Nd title="Nd"}
linker for binary object files
:::

[DESCRIPTION](#DESCRIPTION){.permalink} {#DESCRIPTION .Sh title="Sh"}
=======================================

Most importantly, the old description line "Using LD, the GNU linker"
was completely bogus:

-   The word \"using\" is useless. It goes without saying that a manual
    page first and foremost intends to help with using a program;
    however, it may also help when changing or replacing the program.
-   It is useless to repeat the name in the one-line description, and a
    particularly bad idea to vary the spelling in this place.
-   The one-line description must never specify the source of the
    software. Such information belongs into the AUTHORS and HISTORY
    sections.

::: {.Pp}
:::

What remains is just one single word, "linker". While the one-line
description should indeed be concise, it should also be clear. Even
though it is not usually a complete sentence, having some kind of a
predicate (which action is performed) and some kind of an object (what
does the program operate on) is often helpful.

::: {.Pp}
:::

When designing a one-line description, keep in mind that people often
search for it with
[apropos(1)](http://man.openbsd.org/apropos.1 "Xr"){.Xr}, so try to
include relevant search terms --- of course, without making it sound
awkward. For this reason, "linker for binary object files" is minimally
better than "link binary object files" because people might search for
both "link" or "linker". While "binary object files" might seem slightly
redundant, it is arguably better than just "object files" for the same
reason, and because it avoids the inherent ambiguity of the term
"object".

::: {.Pp}
:::

Time spent polishing the one-line description to be as descriptive and
concise as possible is almost always well spent. It is the very first
thing people see of the manual page, and in the context of
[apropos(1)](http://man.openbsd.org/apropos.1 "Xr"){.Xr}, it\'s all
people have to judge whether that\'s the page they want to read.

::: {.Pp}
:::

Also note the following details:

-   The date format changes.
-   A source string like "binutils-2.17" is no longer needed.
-   The volume string cannot be overridden, no replacement is needed for
    "GNU Development Tools".
-   Section headers need no quoting.
:::

  -------------------- --------
  September 22, 2015   bsd.lv
  -------------------- --------
