Start with my psedo-code

I want a nav bar permanently displayed on left side, size is static, the main body flexes

The right 80% can shrink with window.

After a certain size of shrinking, the nav bar is displayed on top and is scrollable,
the body displays below at that point.


Nav bar sends you to particular point of the documentation body


8-Sep-2023
Currently it looks great, but 2 issues:

1. nav bar is not position: fixed;
    When setting position: fixed;
        It sends ALL my everything else off the rails

2. I can't make background on code element fill the entire width.
    Also want a breakline in the code element that doesn't destroy formatting.
    Tried:
        code {
            width: 100%;
        }

    It did nothing.

9-Sep-2023
The issue was with regard to the checker wanting the ID to match EXACTLY, including
capitalization....  Annoying.  I could go and re-insert the removed sections, but I'm good
for now.