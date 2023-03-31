
Description:
   Auto draw Fibonacci Pivot levels based on the previous (day's, week's or month's)
   Range (High-Low). The HLC3 is used as the default Pivot level.
   Unlike the "Auto Fibonacci Levels", this variation does not update 
   levels on current day even if the price goes past the R3/S3 levels.
   Timeframes: 1D, 1W, 1M

   Range = (High - Low) - From previous Day, Week or month.

   FIB LEVELS:
   - Yellow  = Pivot and Pivot Zone (HLC3 by default)
   - red     = R1,S1 Levels 0.236 * Range
   - Green   = R2,S2 Levels 0.368 * Range
   - Lime    = R3,S3 Levels 0.618 * Range
   - Blue    = R4,S4 Levels 0.786 * Range
   - Gray    = R5,S5 Levels 1.000 * Range
   - Lime    = R6,S6 Levels 1.236 * Range
   - Red     = R7,S7 Levels 1.382 * Range
   - Blue    = R8,S8 Levels 1.618 * Range
   - Green   = R9,S9 Levels 2.000 * Range

   CLASSIC LEVELS:
   - Yellow  = Pivot and Pivot Zone (HLC3)
   - Green   = R1,S1 Levels (Pivot*2 - Low), (Pivot*2 - High)
   - Lime    = R2,S2 Levels (Pivot + Range), (Pivot - Range)
   - Lime    = R3,S3 Levels (High + 2*(Pivot - Low)), (Low - 2*(High - Pivot))
   - Blue    = R4,S4 Levels (High + 3*(Pivot - Low)), (Low - 3*(High - Pivot))

 Refrences:
   - Auto Daily Fib Levels R3.0 by JustUncleL
   - Auto Fib by TheYangGuizi
   - [RS]Monthly Dynamic Range Levels (Fibonaci) V0 by RicardoSantos

 Modifications:
   - Added next FIB Levels. (changes during the current cycle)
   - Added FIB 0.236 Levels
   - Added Option to change the colors of the Fib Levels
   - Changed Default colors to the colors of Tradingview
   - Upgraded to Version4 Pinescript
