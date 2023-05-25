|                                          | transformations |  initial p-value  | result p-value | shapiro p_value | normaltest p_value |
|:------------------------------------------------------------:|:---------------:|:-----------------:|:--------------:|:--------------:|:--------------:|
| Daily total female births in California | [np.diff(lag=1)]]  | 0.881363  | 0.885326 |     0.828834   |
| International airline passengers: monthly totals in thousands | [boxcox, np.diff(lag=1), np.diff(lag=12)]  | 0.881363  | 0.885326 |     0.828834   |
| Mean monthly air temperature (Deg. F) Nottingham Castle | [boxcox, np.diff(lag=1), np.diff(lag=12)]  | 0.881363  | 0.885326 |     0.828834   |
| Monthly Boston armed robberies | [boxcox, np.diff(lag=1)]  | 0.881363  | 0.885326 |     0.828834   |
| Monthly sales of company X | [boxcox, np.diff(lag=1), np.diff(lag=1)]  | 0.881363  | 0.885326 |     0.828834   |
| Weekly closings of the Dow-Jones industrial average | [np.diff(lag=1)]  | 0.881363  | 0.885326 |     0.828834   |
