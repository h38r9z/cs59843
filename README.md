java c
AS 3429/9429 Long Term Actuarial Math II Assignment
Instruction
1.    Students could work individually   or in   a   group   (of maximum   two   members)   to   complete   the   Assignment using Excel (or other mathematical software).
2.    Each student must submit the following two files via Assignments on OWL:
•    One   solution   report   with   the   formulas   and   methods   explained,   required   graphs,    and   appendix (if needed, e.g., R codes).
•    One Excel spreadsheet showing all   the   calculations.
*Note:   If you work in group, please state clearly the group members at the beginning of your   report.
3.    The assignment is due on Friday, Dec 6, by   11:59pm.   For late   submission,   a penalty   of 50%   mark per day will be applied on an hourly basis.
4.   Evaluation:   The assignment will be graded out of a total mark of 50, with weights
40%
Excel
60%
Report
Assignment
1.    Construct   a   special   select   and   ultimate   survival   model   based   on   the   SSSM   (Standard   Select   and Ultimate Survival Model).
Recall that the ultimate part of SSSM assumes Makeham’s Law with:   µx      = A + B · Cx   ,
where A   = 0.00022,    B   = 2.7   × 10−6,    C   =   1.124.   For this new model, you are given:
•    The select period is three   years.
•    Functions for this model are denoted by an   asterisk,   *   .   For all values   of x,
q*[x]      = 0.97q[x];   q*[x]+1    = 0.98q[x]+1;    q*[x]+2    = 0.99q[x]+2;    qx(*)   = qx.Construct a new table for this special   select and   ultimate   survival   model   with   the   valuesof   p*[x]   ,   p*[x−1]+1,   p*[x−2]+2,   px(*)   , l*[x]   , l*[x−1]+1   , l*[x−2]+2   and lx(*)   .   Also,¨(a)x(*)   , Ax(*)   , 2   Ax(*)   ,¨(a)x(*):   10   , Ax(*):   10   ,¨(a)x(*):   20i   ,Ax(*):   20i   ,   5Ex(*)   , 10   Ex(*), 20Ex(*)   ,   ¨(a)x(*)(:   ,   Ax(*)(:   ,   as well   as   ¨(a)*[x]   ,   ¨(a)*[x(]4)   ,   A*[x(]4)   ,   A*[x]   ,   5E]   , 10   E]   ,20   E]   ,   at   integer   ages,   with   limiting   age ω   =   130.    Assume   l2(*)0      =   100,   000   and   interest
rate i   =   5%.   Use UDD for   fractional ages where applicable.
Use the special select and ultimate survival model in   Question   1   for   Questions   2–4.
2.    An insurer issues a 20-year term life insurance policy to a select   life [35].   The sum insured of   $200,000 is payable at the end of   the   year of   death, and   premiums are   paid   annually   throughout   the term of the contract and calculated using   equivalence principle.    The basis for   calculating   premiums and policy values is:
•    Interest:   5% per year effective;
•   Initial Expenses:   $200 plus 25% of the first premium;
•    Renewal Expenses:   $25 plus 5% of each premium after the first year.
(a)    Calculate the gross premium policy   values   at   each   time   t,   for   t   =   0, 1, . . . , 20,   and   plot   them on a graph.   Is there any negative policy value?   If so, explain   the   reason.
(b)    Now   consider   that   the   insurer   earns   an   actual   interest   of   6%   each   year   (mortality   and   expenses are as assumed).   Assume that 80% of   the profit is distributed as cash dividends   to policyholders who are still alive at the end of   the year.   Calculate the代 写AS 3429/9429 Long Term Actuarial Math II AssignmentR
代做程序编程语言 EPV of   the profit   to the insurer per policy issued.   (This is a participating life insurance.)
(c)    Now   assume   that   the   premiums   are   now   paid   quarterly   for   maximum   5   years,   and   the   death benefit is paid   at the   end   of month   of death.    Ignoring   the   expenses,   calculate   the   premium policy values at each year and each premium payment time, and plot them on a   graph.
*Note that the policy values have   jumps at the premium payment time.
3.    Suppose   a   20-year   endowment   insurance   with   sum   insured   $20,000   and   survival   benefit   $10, 000 issued to a select life   [35].   Assume the death benefit is paid at the end of   year of   year,   while the level premiums are paid annually throughout the term of   the contract and calculated   using equivalence principle.   The basis for calculating premiums and policy values is:
•    Interest:   5% per year effective;
•   Initial Expenses:   $200 plus 25% of the first premium;
•    Renewal Expenses:   5% of each premium after the first year.
(a)    Calculate the   gross premium policy values,   net   premium   policy   values   and   FPT   policy   values   at   each   year.       Plot    them    on    a    graph,    and   briefly    discuss   your   conclusion   by   comparing their values.
(b)    Discuss why the premium basis and policy value basis might be different in practice.
4.    Consider   a   continuous   10-year   deferred   10-year   term   life   annuity   of   $2,000   per   year   on   a   selected   life   aged   [35].    A   level   premium   of P   is   payable   continuously   each   year   during   the   first   10 years.   Assume the interest rate is i   =   5%   and   death   are uniformly   distributed   (UDD)   within each year of age.
(a)    Calculate the exact premium rate   P.
(b)   Write out   the   Thiele’s differential equation   for   t   ∈   (0; 20), and   give   any   relevant   boundary   conditions.
(c)   Determine   the   premium   rate   P   by   solving   Thiels’s   differential   equation   using   Euler’s   method, with a time step   h   =   0:05.
(d)    Recalculate   Part   (c)   using   a   time   step   h   =   0:025,   and   compare   the   result   with   Part   (a)   and Part   (c).
(e)    Plot the graph of tV for   t   ∈   (0; 20).
*You may need the “Goal Seek”   function in Excel.
5.    Consider the following model for an insurance policy   combining   disability   income   insurance   benefits and critical illness benefits.
   
The transition intensities are as follows:
01   x
= a1   + b1   exp{c1   x};x(02)   =    a2   + b2   exp{c2   x};
12   x
=         x(02)   ;                              x(32)      =      1:1      x(02)   ;
   
10   x
= 0:1      x(01)   ;                              x(03)      =      0:05
x(01)   ;                              x(13)      =          x(03)   ;
where
a1      = 4   ×   10−4;            b1    =    3:5   ×   10−6;            c1      =      0:14;   a2      =   5   ×   10−4;            b2    =    7:6   ×   10−5;            c2      =      0:09:Using Euler’s method with a   step   size of h   =   0:05,   calculate   values   of 20p30(ij)   for i   =      0; 1   and j   =    0; 1;   2;   3.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
