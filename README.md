# Scripts

TradingView Pine scripts and supporting research artifacts.

Current production candidate: `Simple_Quant_Plus_v2_4_0_Final.pine`.

The script labels Delta/CVD as estimated because it signs 1-minute OHLCV by price direction; it does not receive bid/ask aggressor classification. The default strategy timeframe is 15 minutes as the directly checked baseline, while 5m, 30m and 1h remain selectable rather than being falsely described as defeated alternatives.
