|                                          | transformations |  initial p-value  | result p-value | shapiro p_value | normaltest p_value |
|:------------------------------------------------------------:|:---------------:|:-----------------:|:--------------:|:--------------:|:--------------:|
| Daily total female births in California | [np.diff(lag=1)]]  | 0.000052 | 1.547240e-23 |     0.23546   |  0.61191 |
| International airline passengers: monthly totals in thousands | [boxcox, np.diff(lag=1), np.diff(lag=12)]  | 0.991880  | 2.485912e-04 |     0.04918   | 0.07974|
| Mean monthly air temperature (Deg. F) Nottingham Castle | [boxcox, np.diff(lag=1), np.diff(lag=12)]  | 0.016989 |	1.640728e-22 |	0.25286 |	0.68924 |
| Monthly Boston armed robberies | [boxcox, np.diff(lag=1)]  | 0.994278 |	2.378602e-11 |	0.12342 |	0.68847  |
| Monthly sales of company X | [boxcox, np.diff(lag=1), np.diff(lag=1)]  | 0.988889 |	4.164137e-10 |	0.53576 |	0.77516 |
| Weekly closings of the Dow-Jones industrial average | [np.diff(lag=1)]  | 0.622455 |	2.407586e-24 |	0.92912 |	0.87778 |
