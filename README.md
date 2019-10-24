# Eagle-Library-Pololu
This Pololu Eagle library is an unofficial. If you notice a mistake, please contact the suzaku lab. info@suzakugiken.jp.

非公式のPololu Eagleライブラリです。
ミスに気づいたら朱雀技研 info@suzakugiken.jp までお問い合わせください。

## Pololu Eagle Library
Now in Eagle 6 format.

### Installation (インストール方法)

1. Open Eagle and select the `Control Panel` window.
   Eagleを開きコントロールパネルを選択
2. Choose `Options` and from the drop down that appears, `Directories`.
   OptionからDirectoriesを選択
3. Change the Libraries line from: `$EAGLEDIR/lbr` to something like:
   Librariesの欄を次のように修正

    > $EAGLEDIR/lbr:$HOME/eagle_ext_lbrs (for macOS)

    > $EAGLEDIR\lbr;$HOME\eagle_ext_lbrs (for Windows)

4. Click `OK` to save your changes.
   OKで保存
5. Eagle will prompt to create the directory if it does not already exist.
   Note the location and choose `Yes` to create the directory.
   Yesをクリックしてディレクトリを作成

    > On macOS, `$HOME/eagle_ext_lbrs` changes to: /Users/suzaku/eagle_ext_lbrs/
    
    > On Windows, `$HOME\eagle_ext_lbrs` changes to: C:\Users\suzaku\Documents\eagle_ext_lbrs

6. Find and open the `eagle_ext_lbrs` folder. Unzip and drag `*.lbr` into the 
   new `eagle_ext_lbrs` folder.
   eagle_ext_lbrsを開いて、全てのlbrをコピーしてください。
7. Restart Eagle. The library should be now be usable. 
   Eagleを再起動


### Supported products

- pololu-stepper-dirver.lbr
  - #1182 A4988 Stepper Motor Driver Carrier
  - #2128 A4988 Stepper Motor Driver Carrier; Black Edition
  - #2133 DRV8825 Stepper Motor Driver Carrier; High Current
  - #2134 DRV8834 Low-Voltage Stepper Motor Driver Carrier
  - #2876 STSPIN220 Low-Voltage Stepper Motor Driver Carrier
  - #2877 STSPIN220 Low-Voltage Stepper Motor Driver Carrier (Header Pins Soldered)
  - #2878 STSPIN820 Stepper Motor Driver Carrier
  - #2879 STSPIN820 Stepper Motor Driver Carrier (Header Pins Soldered)
  - #2966 MP6500 Stepper Motor Driver Carrier; Potentiometer Current Control
  - #2967 MP6500 Stepper Motor Driver Carrier; Potentiometer Current Control (Header Pins Soldered)
  - #2968 MP6500 Stepper Motor Driver Carrier; Digital Current Control
  - #2969 MP6500 Stepper Motor Driver Carrier; Digital Current Control (Header Pins Soldered)
  - #2971 DRV8880 Stepper Motor Driver Carrier
  - #2975 A4988 Stepper Motor Driver Carrier (Bulk; No Header Pins)
  - #2976 A4988 Stepper Motor Driver Carrier; Black Edition (Bulk; No Header Pins)
  - #2977 DRV8825 Stepper Motor Driver Carrier; High Current (Bulk; No Header Pins)
  - #2980 A4988 Stepper Motor Driver Carrier (Header Pins Soldered)
  - #2981 A4988 Stepper Motor Driver Carrier; Black Edition (Header Pins Soldered)
  - #2982 DRV8825 Stepper Motor Driver Carrier; High Current (Header Pins Soldered)
  - #2985 A4988 Stepper Motor Driver Carrier (Bulk; Header Pins Soldered)
  - #2986 A4988 Stepper Motor Driver Carrier; Black Edition (Bulk; Header Pins Soldered)
  - #2987 DRV8825 Stepper Motor Driver Carrier; High Current (Bulk; Header Pins Soldered)
  - #3096 TB67S249FTG Stepper Motor Driver Compact Carrier
  - #3097 TB67S249FTG Stepper Motor Driver Compact Carrier (Header Pins Soldered)
  - #3098 TB67S279FTG Stepper Motor Driver Compact Carrier
  - #3099 TB67S279FTG Stepper Motor Driver Compact Carrier (Header Pins Soldered)
