# Scripts

TradingView Pine scripts and supporting research artifacts.

Current production candidate: `Simple_Quant_Plus_v2_8_4_HTF_CHART_CONTEXT_FIXED.pine`.

Simple Quant+ v2.8.4 separates the confirmed Overall Trend and official Trigger/Decision engine from the visible chart-context data. The chart rows support 1m through 1D for DMI/ADX, MOM3/MOM6, estimated flow, EMA20, RVOL and trading ranges, while the official trigger remains on its independently configured 1–60m basis.

Delta/CVD remains explicitly estimated from native 1-minute OHLCV; it is not bid/ask aggressor-classified order flow. Daily Traditional Pivot P/S1/R1 uses the previous completed native 1D H/L/C. Native TradingView compile and live/reload checks remain required before relying on alerts.

Historical candidate retained: `Simple_Quant_Plus_v2_4_0_Final.pine`.
