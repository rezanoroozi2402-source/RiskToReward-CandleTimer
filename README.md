
# Risk To Reward (Candle Timer)

A MetaTrader 5 (MQL5) chart indicator that visualizes your trade's risk/reward setup directly on the chart — a Take Profit zone, a Stop Loss zone, live profit/loss progress fills, an info panel (RR ratio, current R multiple, progress %), and a candle countdown timer & spread panel.

**Creator:** Reza Noroozi
**Telegram:** https://t.me/Rezanoroozifx
**Instagram:** https://www.instagram.com/rezanoroozifx

## Features

- Take Profit / Stop Loss zone rectangles drawn on the chart, each with an independent, fully customizable color
- Live profit/loss progress fills that sit edge-to-edge next to the TP/SL zones (never overlapping or blending colors)
- Info panel showing Risk:Reward ratio, current R multiple, and % progress toward target
- Optional R-ladder levels (1R–5R) and a half-loss warning line
- Candle countdown timer & live spread panel, fully repositionable
- Two display modes: Professional (full detail) and Compact
- All box/panel text auto-fits and scales with font size — no more text spilling outside the boxes

## Installation

1. Download `RiskToReward.mq5` from this repository (or from the latest [Release](../../releases)).
2. Open your MetaTrader 5 data folder: in the terminal, go to **File → Open Data Folder**.
3. Copy `RiskToReward.mq5` into `MQL5/Indicators/`.
4. Open **MetaEditor** (F4 in MT5), open the file, and press **F7** to compile. Make sure it compiles with 0 errors.
5. In MT5's **Navigator** panel, right-click **Custom Indicators → Refresh**, then drag `Risk To Reward` onto your chart.

## Settings overview

| Group | Key inputs | What it controls |
|---|---|---|
| Visibility Toggles | `Show_RR`, `Show_Current_R`, `Show_Progress_Percent`, `Show_Info_Panel`, `Show_TP_Zone`, `Show_SL_Zone`, `Show_Profit_Progress`, `Show_Loss_Progress` | Turn individual panel rows and chart zones on/off |
| Optional R Ladder Levels | `Show_1R_Level` … `Show_5R_Level` | Extra horizontal R-multiple lines above entry/target |
| Half Loss Line | `Show_Half_Loss_Level`, `Half_Loss_Ratio`, `Half_Loss_Line_Color` | A warning line partway between Entry and SL |
| Zone Start | `Zone_Start_Candles_Before_Entry` | How far back (in candles) the zone rectangles start |
| Level Tags | `Level_Label_X_Offset`, `Level_Label_Y_Gap` | Positioning for the R/Half-Loss line labels |
| Display Mode | `Display_Mode` | `DISPLAY_MODE_PROFESSIONAL` or `DISPLAY_MODE_COMPACT` |
| Panel Settings | `Panel_Position`, `Panel_X_Offset`, `Panel_Y_Offset`, `Show_Panel_Background` | Position and background of the main info panel |
| Candle Timer & Spread Panel | `Show_Timer_Spread_Panel`, `Timer_Panel_Position`, `Timer_Panel_X_Offset`, `Timer_Panel_Y_Offset`, `Timer_Panel_Show_Background`, `Timer_Panel_Background_Color`, `Timer_Panel_Background_Alpha`, `Timer_Panel_Text_Color`, `Timer_Panel_Font_Size` | Countdown timer & spread box appearance/position |
| Colors | `TP_Zone_Color`, `SL_Zone_Color`, `Profit_Progress_Color`, `Loss_Progress_Color`, `Entry_Line_Color`, `R_Level_Line_Color`, `Text_Color`, `Panel_Background_Color` | Every drawn element's color, independently |
| Style | `Rectangle_Transparency`, `Font_Size`, `Line_Width` | `Rectangle_Transparency`: 0 = fully solid/opaque color, 100 = fully see-through |
| Performance | `Timer_Interval_Ms` | How often the countdown timer refreshes, in milliseconds |

## Screenshots

<img width="1920" height="990" alt="screenshot2" src="https://github.com/user-attachments/assets/9d0841fe-6881-4509-88d4-f0fbbcfc5d42" />
<img width="1921" height="932" alt="screenshot1" src="https://github.com/user-attachments/assets/b7426459-b70e-452f-8484-8ede356888e4" />

## License

See [LICENSE](LICENSE). Free to use; modification and redistribution are not permitted without the author's permission.

## Contact

Questions, feedback, or feature requests: [Telegram](https://t.me/Rezanoroozifx) or [Instagram](https://www.instagram.com/rezanoroozifx).
