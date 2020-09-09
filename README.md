# LinesOfCode

In order to count the lines, I wrote a program that read in the files as txt documents and parsed the lines.
I used a stream to feed them into the scanner and pulled one line at a time and trimmed it so that there was no whitespace on the edges.
If the string was empty, blanks were increased. If the first two characters were "//" comments were increased.
If "/**" was read, it did not update lines of code, blanks, or comments until it hit "**/" Otherwise, it would increase lines of code.

| Project | File Name | Lines of Code | Blanks | Comments |
| Project1 | Driver.java | 27 | 7 | 4 |
| Project1 | GeneralValue.java | 58 | 25 | 9 |
| Project1 | Point3D.java | 47 | 13 | 7 |
| Project1 | State.java | 63 | 24 | 16 |
| Project1 | Trial.java | 135 | 59 | 34 |
| Project2 | Infant.java | 52 | 9 | 14 |
| Project2 | InvalidValueException.java | 6 | 4 | 4 |
| Project2 | MultipleItemAbstract.java | 57 | 15 | 24 |
| Project2 | Trial.java | 140 | 62 | 37 |
| Project3 | Field.java | 55 | 10 | 12 |
| Project3 | FieldMapper.java | 81 | 20 | 22 |
| Project3 | PointND.java | 56 | 10 | 14 |
| Project5 | KinematicPanel.java | 75 | 13 | 18 |
| Project5 | KinematicPointAbstract.java | 63 | 18 | 12 |
| Project5 | KinematicPointConstant.java | 34 | 6 | 5 |
| Project5 | KinematicPointState.java | 27 | 5 | 3 |
