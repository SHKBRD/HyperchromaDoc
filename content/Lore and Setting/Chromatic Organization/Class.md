# Basic Overview

Every [[Chromatics|Chromatic]] is ranked amongst other Chromatics via their Class. The Class Rank indicates the Chromatic's skill in fighting opposing Chromatics, and it is increased via earning credits. All Chromatics start out with a Class rank of Class 1. The highest Class that a Chromatic can reach via credits is Class 9, though exactly one Chromatic at any given time can also have the [[Class 10]] ranking, which is awarded upon killing the current Class 10.

A Chromatic's current Class is indicated via their [[Rank Badge]].

credits are only rewarded if a Chromatic, using their own weapon, successfully lands the last lethal wound upon an opposing Chromatic. This must be done using the Chromatic's assigned weapon, since the blood of the opposing Chromatic will be [[Mesh Metal|stored in their blade]], which is then later used to credit the Chromatic if they [[Weapon Rinsing|rinse their weapon]]. If that Chromatic was the last person to land a lethal wound upon the opposing Chromatic, and the opposing Chromatic is dead by the time the weapon is rinsed, the surviving Chromatic is then awarded credits.

It should be noted that until a Chromatic's weapon is rinsed, a Chromatic's Class will remain the same even if they earn enough credits to qualify for a Class promotion.

The credit requirement to promote to a higher Class is the same as the Chromatic's current rank. For example, a Class 5 Chromatic will need to acquire 5 credits in order to reach Class 6, and a Class 3 Chromatic would need 3 credits to promote to Class 4, etc.

# More Details

The amount of credits awarded per each kill is primarily based on the difference in Class between the two Chromatics. If there is no difference between the two Chromatic's classes, one credit is awarded. If there is a difference, the awarded credits are multiplied or divided by two for every Class higher or lower than the surviving Chromatic.

In the event that a Chromatic earns more credits than required for a particular rank, the leftover credits are carried over after the promotion.

For example:

A Class 1 kills a Class 2, which earns them 2 credits. After fulfilling the 1 credit requirement to rank up to Class 2, the Chromatic is credited the remaining 1 credit to count towards the new credit requirement. As a result of the initial kill, the Class 1 Chromatic with 0 credits is now a Class 2 Chromatic with 1 credit.

To prevent overwhelming Class rank promotions via higher Class differences, the highest Class that a Chromatic can attain is the Class rank of the highest Class opponent that the Chromatic has ever killed, plus one. 

For example, if a Class 1 Chromatic somehow kills three Class 4 Chromatics back to back, and earns 24 credits as a result, that Chromatic cannot rank up past Class 5. After rinsing their weapon, they would be a Class 5 Chromatic with 9 (24-5-4-3-2-1) credits. Any remaining credits will not go towards a promotion until they kill a Chromatic with a Class rank that is at least as high as their own.

A Chromatic can also earn more credits if they kill their opponent without being wounded by their opponent. Successfully doing this will double the base credit count, which will significantly reduce the amount of kills needed to reach the Chromatic's next promotion.

# Math Stuff

Here are some fun tables.

The formula for the earned credits is as follows:

Co -> Opposing Chromatic's Class
Cs -> Surviving Chromatic's Class
# $2_{}^{\left(C_{o}-C_{s}\right)}$

| Class Difference upon Kill | Base credits Awarded |
| :------------------------: | :------------------------: |
|             -9             |        0.001953125         |
|             -8             |         0.00390625         |
|             -7             |         0.0078125          |
|             -6             |          0.015625          |
|             -5             |          0.03125           |
|             -4             |           0.0625           |
|             -3             |           0.125            |
|             -2             |            0.25            |
|             -1             |            0.5             |
|             0              |             1              |
|             1              |             2              |
|             2              |             4              |
|             3              |             8              |
|             4              |             16             |
|             5              |             32             |
|             6              |             64             |
|             7              |            128             |
|             8              |            256             |
|             9              |            512             |


Total required kills for an individual Chromatic to attain a rank (assuming no Class differences among all kills)

| Class | Total required kills for an individual Chromatic to attain a rank (No Class Difference) |
| :---: | :-------------------------------------------------------------------------------------: |
|   1   |                  1 ([[Chromatic Eligibility Exam\|Eligibility Exam]])                   |
|   2   |                                            2                                            |
|   3   |                                            4                                            |
|   4   |                                            7                                            |
|   5   |                                           11                                            |
|   6   |                                           16                                            |
|   7   |                                           22                                            |
|   8   |                                           29                                            |
|   9   |                                           37                                            |
|  10   |                                           N/A                                           |

Chromatics needed to be killed in order for one Chromatic to attain a particular Class, assuming no Class differences between any kills. These are not necessarily the amounts of Chromatics that a single Chromatic must kill in order to reach these classes.

| Class |        Total Chromatics killed to reach Class        |
| :---: | :--------------------------------------------------: |
|   1   | 1 ([[Chromatic Eligibility Exam\|Eligibility Exam]]) |
|   2   |                          2                           |
|   3   |                          6                           |
|   4   |                          21                          |
|   5   |                          88                          |
|   6   |                         445                          |
|   7   |                         2676                         |
|   8   |                        18739                         |
|   9   |                        149920                        |
|  10   |                         N/A                          |
