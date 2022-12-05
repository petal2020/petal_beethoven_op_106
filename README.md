# petal_beethoven_op_106
data sets for performance analyses of Ludwig van Beethoven’s 'Hammerklavier' Sonata op. 106, third movement *Adagio sostenuto* (1817–18)

This repository introduces data sets created during research on recorded performances of the third movement *Adagio sostenuto* of Ludwig van Beethoven’s 'Hammerklavier' Sonata op. 106 (1817–18). It complements the following article:

Utz, Christian. 2022. “Form-Functional Ambivalence in Performance: The Third Movement of Beethoven’s ‘Hammerklavier’ Sonata in Recordings by Gulda, Brendel, and other Pianists.” *Music Theory & Analysis* 9, no. 2.

Audio and video examples as well as an annotated score of the analyzed movement can be accessed at https://phaidra.kug.ac.at/o:127822.
Audio measurements and data collection were done by Laurence Sinclair Willis.

# main content

All data are provided in **one Excel file** with **nine worksheets**.

(1) **Worksheet #1: discography** contains discographic information on the 27 analyzed recordings including duration and main tempo of movement iii (values derived from worksheets 2 and 3) with main, maximum, and minimum values. A second table reduces the corpus to 21 recordings by removing multiple recordings of the same pianist.

(2) **Worksheet #2: data_seg** provides average tempo values (in beats per minute; bpm) for each segment of the movement (rows 1–122). The movement is divided into 120 segments (see annotated score at https://phaidra.kug.ac.at/o:127813). The left column for each recording provides raw time points exported from Sonic Visualiser, the right column calculates the mean tempo value for the respective segment. Rows 124–125 provide the total duration for each recording. Rows 128–143 provide the durations of each formal section (16 formal sections are distinguished for this movement) for all recordings. The relative weight for each section in all recordings based on sectional durations is provided in rows 148–163.

(3) **Worksheet #3: data_bpb** provides bpm tempo values for every bar of the movement for seven recordings based on raw time points exported from Sonic Visualiser (columns I–O). The mean tempo value of all 187 bars is calculated in row 190.

(4) **Worksheet #4: tpo_bars** calculates bpm tempo values for each bar also for those recordings that were only measured by segments using the formulas provided in column C. For each recording the right and middle column are linked to the two columns of the respective recordings in Worksheet #2 (data_seg). The left column calculates the bpm value for each bar. 

(5) **Worksheet #5: tpo+dev_bars_seg_sec** reproduces the bar-by-bar tempo values of Worksheet #4 (rows 2–188), calculates the main tempo of each section (rows 193–208), excluding bars with indicated tempo variation, and a main tempo of the entire movement by calculating a weighted average from the 16 sectional main tempo values. In addition, the relative tempo change in three prominent ritardando sections is provided in logarithmic form in rows 210–212 (see Worksheet #8). Finally, for each section the logarithmic deviation from the mean value of all 27 recordings of the respective section is provided (rows 216–231 and 236–422).

(6) **Worksheet #6: tpo_overview** brings together the sectional main tempi into a table with the relative position of each tempo value indicated by color gradations for each section. Deviations of analogous sections from exposition and recapitulation are provided in logarithmic form (rows 19–26). Deviations from sectional means are reporduced in rows 29–44. From these values the Pearson correlation table in rows 47–73 is derived.

(7) **Worksheet #7: main_tpo_sec** reproduces the sectional main tempi in different form that facilitates the additional tables of data sorted according to the relative standard deviation of all (16) sections in a recording (columns Y–AA), according to the relative standard deviation of all (120) segments in a recording (columns AC–AD), and according to the main tempo value (columns AF–AJ).

(8) **Worksheet #8: rit** rearranges the relative tempo changes in three prominent ritardando sections calculated in Worksheet #5 (logarithmic values). The tables in columns I–T provide sorted data for these ritardando sections in two different forms each.

(9) **Worksheet #9: dev** rearranges the deviations of analogous formal sections in each recording calculated in Worksheet #6. 
