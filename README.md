## :capital_abcd: Chrome Fonts

Fonts that Google recommends to have when running Puppeteer:

- https://github.com/puppeteer/puppeteer/blob/main/docs/troubleshooting.md#running-puppeteer-in-docker
- https://github.com/puppeteer/puppeteer/blob/main/docker/Dockerfile#L14

You can install those fonts on your Ubuntu system by running:

```shell
apt-get update
apt-get install -y fonts-ipafont-gothic fonts-wqy-zenhei fonts-thai-tlwg fonts-khmeros fonts-kacst fonts-freefont-ttf fonts-liberation
```

Or download them from the `fonts` directory inside this repository, which contains those same font files that would be installed into `/usr/share/fonts` by the command above.

The complete list of fonts include:

```shell
/usr/share/fonts/truetype/tlwg/TlwgTypo-Bold.ttf: Tlwg Typo:style=Bold
/usr/share/fonts/truetype/dejavu/DejaVuSerif-Bold.ttf: DejaVu Serif:style=Bold
/usr/share/fonts/truetype/freefont/FreeSansOblique.ttf: FreeSans:style=Oblique,наклонен,cursiva,kurzíva,kursiv,Πλάγια,Kursivoitu,Italique,Dőlt,Corsivo,Cursief,kursywa,Itálico,oblic,Курсив,İtalik,huruf miring,похилий,Ležeče,slīpraksts,pasvirasis,nghiêng,Etzana,तिरछा,বাঁকা
/usr/share/fonts/truetype/tlwg/TlwgTypewriter-BoldOblique.ttf: Tlwg Typewriter:style=Bold Oblique
/usr/share/fonts/truetype/dejavu/DejaVuSansMono.ttf: DejaVu Sans Mono:style=Book
/usr/share/fonts/truetype/tlwg/Garuda.ttf: Garuda:style=Regular
/usr/share/fonts/truetype/liberation/LiberationSansNarrow-Italic.ttf: Liberation Sans Narrow:style=Italic
/usr/share/fonts/truetype/kacst/KacstFarsi.ttf: KacstFarsi:style=Medium
/usr/share/fonts/truetype/dejavu/DejaVuSans.ttf: DejaVu Sans:style=Book
/usr/share/fonts/truetype/freefont/FreeSansBoldOblique.ttf: FreeSans:style=Bold Oblique,получерен наклонен,negreta cursiva,tučné kurzíva,fed kursiv,Fett-Kursiv,Έντονη Πλάγια,Negrita Cursiva,Lihavoitu Kursivoi,Gras Italique,Félkövér dőlt,Grassetto Corsivo,Vet Cursief,Halvfet Kursiv,Pogrubiona kursywa,Negrito Itálico,gros oblic,Полужирный Курсив,Tučná kurzíva,Fet Kursiv,Kalın İtalik,huruf tebal miring,жирний похилий,polkrepko ležeče,treknais slīpraksts,pusjuodis pasvirasis,nghiêng đậm,Lodi etzana,धृष्ट-तिरछा
/usr/share/fonts/truetype/ttf-khmeros/KhmerOSsiemreap.ttf: Khmer OS Siemreap:style=Regular
/usr/share/fonts/opentype/ipafont-mincho/ipam.ttf: IPAMincho,IPA明朝:style=Regular
/usr/share/fonts/truetype/kacst/mry_KacstQurn.ttf: mry_KacstQurn:style=Regular
/usr/share/fonts/truetype/tlwg/TlwgTypist.ttf: Tlwg Typist:style=Regular
/usr/share/fonts/truetype/kacst-one/KacstOne-Bold.ttf: KacstOne:style=Bold
/usr/share/fonts/truetype/freefont/FreeMonoBoldOblique.ttf: FreeMono:style=Bold Oblique,получерен наклонен,Negreta cursiva,tučné kurzíva,fed kursiv,Fett-Kursiv,Έντονα Πλάγια,Negrita Cursiva,Lihavoitu Kursivoi,Gras Italique,Félkövér dőlt,Grassetto Corsivo,Vet Cursief,Halvfet Kursiv,Pogrubiona kursywa,Negrito Itálico,gros oblic,Полужирный Курсив,Tučná kurzíva,Fet Kursiv,Kalın İtalik,huruf tebal miring,жирний похилий,polkrepko ležeče,treknais slīpraksts,pusjuodis pasvirasis,Lodi etzana,धृष्ट-तिरछा
/usr/share/fonts/truetype/liberation/LiberationSans-Regular.ttf: Liberation Sans:style=Regular
/usr/share/fonts/truetype/liberation/LiberationMono-BoldItalic.ttf: Liberation Mono:style=Bold Italic
/usr/share/fonts/truetype/tlwg/Loma-Oblique.ttf: Loma:style=Oblique
/usr/share/fonts/truetype/liberation/LiberationSerif-Italic.ttf: Liberation Serif:style=Italic
/usr/share/fonts/truetype/kacst/KacstDigital.ttf: KacstDigital:style=Medium
/usr/share/fonts/truetype/tlwg/TlwgTypo-Oblique.ttf: Tlwg Typo:style=Oblique
/usr/share/fonts/truetype/kacst/KacstPen.ttf: KacstPen:style=Medium
/usr/share/fonts/truetype/liberation/LiberationMono-Bold.ttf: Liberation Mono:style=Bold
/usr/share/fonts/truetype/tlwg/Laksaman-Italic.ttf: Laksaman:style=Italic
/usr/share/fonts/truetype/tlwg/Kinnari-Italic.ttf: Kinnari:style=Italic
/usr/share/fonts/truetype/tlwg/TlwgMono-Bold.ttf: Tlwg Mono:style=Bold
/usr/share/fonts/truetype/tlwg/Waree.ttf: Waree:style=Regular
/usr/share/fonts/truetype/wqy/wqy-zenhei.ttc: WenQuanYi Zen Hei,文泉驛正黑,文泉驿正黑:style=Regular
/usr/share/fonts/truetype/tlwg/Kinnari-Oblique.ttf: Kinnari:style=Oblique
/usr/share/fonts/truetype/tlwg/Umpush-BoldOblique.ttf: Umpush:style=Bold Oblique
/usr/share/fonts/truetype/liberation/LiberationSansNarrow-Regular.ttf: Liberation Sans Narrow:style=Regular
/usr/share/fonts/truetype/ttf-khmeros/KhmerOSmetalchrieng.ttf: Khmer OS Metal Chrieng:style=Regular
/usr/share/fonts/truetype/wqy/wqy-zenhei.ttc: WenQuanYi Zen Hei Sharp,文泉驛點陣正黑,文泉驿点阵正黑:style=Regular
/usr/share/fonts/truetype/tlwg/Umpush-Oblique.ttf: Umpush:style=Oblique
/usr/share/fonts/truetype/tlwg/Sawasdee-Bold.ttf: Sawasdee:style=Bold
/usr/share/fonts/truetype/kacst/KacstScreen.ttf: KacstScreen:style=Medium,KacstScreen
/usr/share/fonts/truetype/kacst/KacstArt.ttf: KacstArt:style=Medium
/usr/share/fonts/truetype/freefont/FreeSerif.ttf: FreeSerif:style=Regular,нормален,normal,obyčejné,Mittel,µεσαία,Normaali,Normál,Normale,Gemiddeld,odmiana zwykła,Обычный,Normálne,ปกติ,menengah,прямій,Navadno,vidējs,normalusis,عادی,vừa,Arrunta,सामान्य,সাধারণ,ସାମାନ୍ଯ,സാധാരണ,ނުވަތަ މެދު,ਸਾਧਾਰਨ,साधारण
/usr/share/fonts/truetype/ttf-khmeros/KhmerOSmuolpali.ttf: Khmer OS Muol Pali:style=Regular
/usr/share/fonts/truetype/freefont/FreeSansBold.ttf: FreeSans:style=Bold,получерен,negreta,tučné,fed,Fett,Έντονα,Negrita,Lihavoitu,Gras,Félkövér,Grassetto,Vet,Halvfet,Pogrubiony,Negrito,gros,Полужирный,Fet,Kalın,huruf tebal,жирний,Krepko,treknraksts,pusjuodis,đậm,Lodia,धृष्ट,സ്പഷ്ട,ठळक,बाक्लो
/usr/share/fonts/truetype/dejavu/DejaVuSansMono-Oblique.ttf: DejaVu Sans Mono:style=Oblique
/usr/share/fonts/truetype/dejavu/DejaVuSans-Bold.ttf: DejaVu Sans:style=Bold
/usr/share/fonts/truetype/tlwg/Norasi-BoldItalic.ttf: Norasi:style=Bold Italic
/usr/share/fonts/truetype/liberation/LiberationSerif-Bold.ttf: Liberation Serif:style=Bold
/usr/share/fonts/truetype/dejavu/DejaVuSansMono-BoldOblique.ttf: DejaVu Sans Mono:style=Bold Oblique
/usr/share/fonts/truetype/tlwg/Laksaman-Bold.ttf: Laksaman:style=Bold
/usr/share/fonts/truetype/tlwg/Purisa-Bold.ttf: Purisa:style=Bold
/usr/share/fonts/truetype/tlwg/Waree-Oblique.ttf: Waree:style=Oblique
/usr/share/fonts/truetype/ttf-khmeros-core/KhmerOS.ttf: Khmer OS:style=Regular
/usr/share/fonts/truetype/liberation/LiberationMono-Regular.ttf: Liberation Mono:style=Regular
/usr/share/fonts/truetype/ttf-khmeros/KhmerOSfreehand.ttf: Khmer OS Freehand:style=Regular
/usr/share/fonts/truetype/tlwg/Norasi-BoldOblique.ttf: Norasi:style=Bold Oblique
/usr/share/fonts/truetype/tlwg/Garuda-Bold.ttf: Garuda:style=Bold
/usr/share/fonts/truetype/liberation/LiberationSans-Italic.ttf: Liberation Sans:style=Italic
/usr/share/fonts/truetype/tlwg/Loma.ttf: Loma:style=Regular
/usr/share/fonts/truetype/tlwg/TlwgTypist-Oblique.ttf: Tlwg Typist:style=Oblique
/usr/share/fonts/truetype/freefont/FreeSerifBoldItalic.ttf: FreeSerif:style=Bold Italic,получерен курсивен,negreta itàlica,tučné kurzíva,fed kursiv,Fett-Kursiv,Negrita Cursiva,Lihavoitu Kursivoi,Gras Italique,Félkövér dőlt,Grassetto Corsivo,Vet Cursief,Halvfet Kursiv,Pogrubiona kursywa,Negrito Itálico,gros cursiv,Полужирный Курсив,Tučná kurzíva,Fet Kursiv,ตัวเอียงหนา,Kalın İtalik,huruf tebal kursif,жирний курсив,Polkrepko Pežeče,treknais kursīvs,pusjuodis kursyvas,nghiêng đậm,Lodi etzana,धृष्ट-तिरछा
/usr/share/fonts/truetype/ttf-khmeros-core/KhmerOSsys.ttf: Khmer OS System:style=Regular
/usr/share/fonts/truetype/tlwg/Purisa-BoldOblique.ttf: Purisa:style=Bold Oblique
/usr/share/fonts/truetype/liberation/LiberationSerif-BoldItalic.ttf: Liberation Serif:style=Bold Italic
/usr/share/fonts/truetype/tlwg/TlwgTypewriter-Bold.ttf: Tlwg Typewriter:style=Bold
/usr/share/fonts/truetype/tlwg/TlwgTypo.ttf: Tlwg Typo:style=Regular
/usr/share/fonts/truetype/freefont/FreeMonoOblique.ttf: FreeMono:style=Oblique,наклонен,cursiva,kurzíva,kursiv,Πλάγια,Kursivoitu,Italique,Dőlt,Corsivo,Cursief,Kursywa,Itálico,oblic,Курсив,İtalik,huruf miring,похилий,ležeče,slīpraksts,pasvirasis,nghiêng,Etzana,तिरछा
/usr/share/fonts/truetype/tlwg/Norasi-Bold.ttf: Norasi:style=Bold
/usr/share/fonts/truetype/tlwg/Sawasdee-Oblique.ttf: Sawasdee:style=Oblique
/usr/share/fonts/truetype/tlwg/Kinnari-Bold.ttf: Kinnari:style=Bold
/usr/share/fonts/truetype/tlwg/Umpush-Light.ttf: Umpush:style=Light
/usr/share/fonts/truetype/tlwg/Waree-BoldOblique.ttf: Waree:style=Bold Oblique
/usr/share/fonts/truetype/liberation/LiberationSansNarrow-BoldItalic.ttf: Liberation Sans Narrow:style=Bold Italic
/usr/share/fonts/truetype/dejavu/DejaVuSansMono-Bold.ttf: DejaVu Sans Mono:style=Bold
/usr/share/fonts/truetype/tlwg/Garuda-Oblique.ttf: Garuda:style=Oblique
/usr/share/fonts/truetype/ttf-khmeros/KhmerOSmuol.ttf: Khmer OS Muol:style=Regular
/usr/share/fonts/truetype/kacst/KacstDecorative.ttf: KacstDecorative:style=Medium
/usr/share/fonts/truetype/tlwg/Norasi.ttf: Norasi:style=Regular
/usr/share/fonts/opentype/ipafont-gothic/ipag.ttf: IPAGothic,IPAゴシック:style=Regular
/usr/share/fonts/truetype/tlwg/Garuda-BoldOblique.ttf: Garuda:style=Bold Oblique
/usr/share/fonts/truetype/fonts-japanese-mincho.ttf: IPAMincho,IPA明朝:style=Regular
/usr/share/fonts/truetype/tlwg/Laksaman-BoldItalic.ttf: Laksaman:style=Bold Italic
/usr/share/fonts/truetype/tlwg/Sawasdee-BoldOblique.ttf: Sawasdee:style=Bold Oblique
/usr/share/fonts/truetype/tlwg/TlwgTypist-Bold.ttf: Tlwg Typist:style=Bold
/usr/share/fonts/truetype/tlwg/Sawasdee.ttf: Sawasdee:style=Regular
/usr/share/fonts/truetype/tlwg/TlwgMono.ttf: Tlwg Mono:style=Regular
/usr/share/fonts/truetype/ttf-khmeros/KhmerOSmuollight.ttf: Khmer OS Muol Light:style=Regular
/usr/share/fonts/truetype/liberation/LiberationMono-Italic.ttf: Liberation Mono:style=Italic
/usr/share/fonts/truetype/liberation/LiberationSans-BoldItalic.ttf: Liberation Sans:style=Bold Italic
/usr/share/fonts/truetype/tlwg/Umpush-Bold.ttf: Umpush:style=Bold
/usr/share/fonts/truetype/tlwg/TlwgMono-Oblique.ttf: Tlwg Mono:style=Oblique
/usr/share/fonts/truetype/tlwg/TlwgTypewriter.ttf: Tlwg Typewriter:style=Regular
/usr/share/fonts/truetype/tlwg/Kinnari.ttf: Kinnari:style=Regular
/usr/share/fonts/truetype/tlwg/Purisa.ttf: Purisa:style=Regular
/usr/share/fonts/truetype/tlwg/Norasi-Oblique.ttf: Norasi:style=Oblique
/usr/share/fonts/truetype/ttf-khmeros/KhmerOSbokor.ttf: Khmer OS Bokor:style=Regular
/usr/share/fonts/truetype/tlwg/Loma-Bold.ttf: Loma:style=Bold
/usr/share/fonts/truetype/ttf-khmeros/KhmerOSfasthand.ttf: Khmer OS Fasthand:style=Regular
/usr/share/fonts/truetype/ttf-khmeros/KhmerOSbattambang.ttf: Khmer OS Battambang:style=Regular
/usr/share/fonts/truetype/liberation/LiberationSerif-Regular.ttf: Liberation Serif:style=Regular
/usr/share/fonts/truetype/tlwg/Purisa-Oblique.ttf: Purisa:style=Oblique
/usr/share/fonts/truetype/kacst/KacstTitleL.ttf: KacstTitleL:style=Medium,Regular
/usr/share/fonts/truetype/fonts-japanese-gothic.ttf: IPAGothic,IPAゴシック:style=Regular
/usr/share/fonts/truetype/ttf-khmeros/KhmerOScontent.ttf: Khmer OS Content:style=Regular
/usr/share/fonts/truetype/kacst-one/KacstOne.ttf: KacstOne:style=Regular
/usr/share/fonts/truetype/kacst/KacstLetter.ttf: KacstLetter:style=Medium
/usr/share/fonts/truetype/wqy/wqy-zenhei.ttc: WenQuanYi Zen Hei Mono,文泉驛等寬正黑,文泉驿等宽正黑:style=Regular
/usr/share/fonts/truetype/tlwg/TlwgMono-BoldOblique.ttf: Tlwg Mono:style=Bold Oblique
/usr/share/fonts/truetype/tlwg/Norasi-Italic.ttf: Norasi:style=Italic
/usr/share/fonts/truetype/freefont/FreeSerifBold.ttf: FreeSerif:style=Bold,получерен,negreta,tučné,fed,Fett,Negrita,Lihavoitu,Gras,Félkövér,Grassetto,Vet,Halvfet,Pogrubiony,Negrito,gros,Полужирный,Fet,ตัวหนา,Kalın,huruf tebal,жирний,Polkrepko,treknraksts,pusjuodis,ضخیم,đậm,Lodia,धृष्ट,ମୋଟା,സ്പഷ്ട,ठळक,ފަވާފައ,ਮੋੱਟਾ,बाक्लो
/usr/share/fonts/truetype/tlwg/Laksaman.ttf: Laksaman:style=Regular
/usr/share/fonts/truetype/liberation/LiberationSansNarrow-Bold.ttf: Liberation Sans Narrow:style=Bold
/usr/share/fonts/truetype/tlwg/Kinnari-BoldOblique.ttf: Kinnari:style=Bold Oblique
/usr/share/fonts/truetype/liberation/LiberationSans-Bold.ttf: Liberation Sans:style=Bold
/usr/share/fonts/truetype/freefont/FreeMono.ttf: FreeMono:style=Regular,нормален,normal,obyčejné,Standard,µεσαία,Normaali,Normál,Normale,Standaard,Normalny,Обычный,Normálne,menengah,прямій,navadno,vidējs,normalusis,thường,Arrunta,सामान्य
/usr/share/fonts/truetype/tlwg/Kinnari-BoldItalic.ttf: Kinnari:style=Bold Italic
/usr/share/fonts/truetype/tlwg/Loma-BoldOblique.ttf: Loma:style=Bold Oblique
/usr/share/fonts/truetype/tlwg/TlwgTypo-BoldOblique.ttf: Tlwg Typo:style=Bold Oblique
/usr/share/fonts/truetype/kacst/KacstBook.ttf: KacstBook:style=Medium
/usr/share/fonts/truetype/kacst/KacstPoster.ttf: KacstPoster:style=Medium
/usr/share/fonts/truetype/tlwg/TlwgTypewriter-Oblique.ttf: Tlwg Typewriter:style=Oblique
/usr/share/fonts/truetype/freefont/FreeSerifItalic.ttf: FreeSerif:style=Italic,курсивен,itàlica,kurzíva,kursiv,Λειψίας,Cursiva,Kursivoitu,Italique,Dőlt,Corsivo,Cursief,kursywa,Itálico,cursiv,Курсив,ตัวเอียง,İtalik,kursif,Ležeče,kursīvs,kursivas,nghiêng,Etzana,तिरछा,তির্যক
/usr/share/fonts/truetype/tlwg/TlwgTypist-BoldOblique.ttf: Tlwg Typist:style=Bold Oblique
/usr/share/fonts/truetype/kacst/KacstQurn.ttf: KacstQurn:style=Medium,Regular
/usr/share/fonts/truetype/freefont/FreeSans.ttf: FreeSans:style=Regular,нормален,Normal,obyčejné,Mittel,µεσαία,Normaali,Normál,Medio,Gemiddeld,Odmiana Zwykła,Обычный,Normálne,menengah,прямій,Navadno,vidējs,normalusis,vừa,Arrunta,सामान्य,সাধারণ,സാധാരണ,साधारण
/usr/share/fonts/truetype/kacst/KacstNaskh.ttf: KacstNaskh:style=Medium
/usr/share/fonts/truetype/dejavu/DejaVuSerif.ttf: DejaVu Serif:style=Book
/usr/share/fonts/truetype/freefont/FreeMonoBold.ttf: FreeMono:style=Bold,получерен,negreta,tučné,fed,Fett,Έντονα,Negrita,Lihavoitu,Gras,Félkövér,Grassetto,Vet,Halvfet,Pogrubiony,Negrito,gros,Полужирный,Fet,Kalın,huruf tebal,жирний,polkrepko,treknraksts,pusjuodis,đậm,Lodia,धृष्ट
/usr/share/fonts/opentype/ipafont-mincho/ipamp.ttf: IPAPMincho,IPA P明朝,䥐䅐䵩湣桯:style=Regular
/usr/share/fonts/truetype/tlwg/Waree-Bold.ttf: Waree:style=Bold
/usr/share/fonts/truetype/tlwg/Umpush-LightOblique.ttf: Umpush:style=Light Oblique
/usr/share/fonts/truetype/tlwg/Umpush.ttf: Umpush:style=Regular
/usr/share/fonts/truetype/kacst/KacstTitle.ttf: KacstTitle:style=Medium
/usr/share/fonts/opentype/ipafont-gothic/ipagp.ttf: IPAPGothic,IPA Pゴシック,䥐䅐䝯瑨楣:style=Regular
/usr/share/fonts/truetype/kacst/KacstOffice.ttf: KacstOffice:style=Medium
```

