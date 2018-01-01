# Decorations

Decorations

Description

The Sultan of Sylvania loves throwing parties, because that gives him a reason to decorate the palace.He particularly likes decorations called streamers made up of diffrent beads strung together on a string and hung from the ceiling. Now, like most Sultans, he is very particular about everything, including these strung decorations. Specifically, he only likes certain combinations of beads to be used on the streamers. For example, if there are four diffrent types of beads - A, B, C and D - the Sultan might say "It pleases his highness that only the combinations ABB, BCA, BCD, CAB, CDD and DDA appear in the streamers at tonight's party". This, needless to say, puts a severe limit on the number of diffrent streamers possible. For example, if the length of the streamers was 5, then the only possible streams of beads would be BCABB and BCDDA (strings such as ABBCA could not be used because BBC is not an approved combination). Since the Sultan likes variety, it is important to know the total number of streamers possible, given a length and the current bead combinations which tickle the Sultan's fancy.

Input

Input will consist of multiple test cases. Each case will consist of two lines. The first line will contain three positive integers n, l and m, where n indicates the number of bead types, l is the length of the streamers and m indicates the number of bead combinations which the Sultan likes. The maximum values for n, l and m will be 26, 100 and 600, respectively. The next line will contain the m combinations.Each combination will be of the same length (between 1 and 10) and will be separated using a single space. All combinations will make use of only the uppercase letters of the alphabet. An input line of 0 0 0 will terminate input and should not be processed.

Output

For each test case, output a single line indicating the number of possible streamers. All answers will be within the range of a 32-bit integer.

Sample Input

4 5 6
ABB BCA BCD CAB CDD DDA
5 4 5
E D C B A
4 8 3
AA BB CC
0 0 0

Sample Output

2
625
3
