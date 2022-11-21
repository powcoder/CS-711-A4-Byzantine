https://powcoder.com
代写代考加微信 powcoder
Assignment Project Exam Help
Add WeChat powcoder
Test scenarios for the Byzantine agreement project

The .txt file encoding is best described by an example

Consider file byz-4-2.x.txt

4 2 0
1 0 1 0 0 1 1 011 011 011 011 
2 0 0 
4 1 0 
3 1 0 

Line #0: N=4, L=2, V0=0

Line #2: PID=2, init v=0, faulty=0 (not faulty)
Line #3: PID=4, init v=1, faulty=0 (not faulty)
Line #4: PID=3, init v=1, faulty=0 (not faulty)

Line #1: PID=1, init v=0; faulty=1 (faulty!); 
the rest of the line describe its script, that corresponds to the two level messages

0 0 1 1
011 011 011 011

