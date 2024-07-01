## Introduction
The briefing includes background info on Klumgongyn, and his letter. The instructions indicate that the password is in the letter, which needs to be translated into English.

### 1. Transposing the original text

I first took the original text from the briefing and assigned a random letter or number to each character so I could type the cipher out as a new cipher using the latin alphabet. The new, transposed cipher is below:

> ABCCD EFBGHIC IJBKL, HL'E KHGB LD EBB MDN IJIHK. LAIKOE PDR EISHKJ TM CHPB BIRCHBR LAHE MBIR. LAIL UIE VNHLB LAB IWSBKLNRB. BSBR EHKGB JBLLHKJ DPP MDNR FCIKBL H'SB THEEBW LAHE FCIGB JRBILCM. BSBK LADNJA MDNR OHKW GIK XB GRNBC, ELRIKJB IKW SHDCBKL HL FRDSHWBE I UDKWBRPNC ADTB PHCCBW UHLA ADFB PDR LAB PNLNRB.

> HL HE LABRBPDRB LAIL H'SB WBGHWBW LD YDHK MDNR FCIKBL DP AIHRCBEE IFBE. IPLBR GDKENCLHKJ UHLA LAB DSBREBBR, UB AISB RBIGABW IK IJRBBTBKL LAIL H UHCC XBGDTB MDNR KBU GDNKGBC CBIWBR, TBIKHKJ LABRB HE KDU I WHRBGL CHKO XBLUBBK LAB OCNTJDKE IKW BIRLACHKJE TIOHKJ XDLA DNR FDEHLHDKE HK LAB JICIZHBE TNGA ELRDKJBR. TDELCM MDNRE, EHKGB UB IRB IXEDCNLB CHJALMBIRE IABIW DP MDNR ELBITFNKO LBGAKDCDJM IKW "THGRD" GAHFE.

> H IT ICED FCBIEBW LD CBIRK LAIL MDN IRB ELHCC LAB LDF EFBGHIC IJBKL. LAHE LIEO HE WBEHJKBW LD HWBKLHPM HP MDN IRB LRNCM "LAB DKB". NFDK GDTFCBLHDK MDN EAICC RBGBHSB LAB PHCBE LD NEB LAB IKGHBKL OCNTJDK CIKJNIJB. HL UIE URHLLBK XM ZMKLDCMR, DKB DP LAB PHREL BCWBRE DP DNR DKCM LRHXB IL LAB LHTB.

> DNR CIKJNIJB UIE PDNKWBW 123456 MBIRE IJD! LAHE TIOBE HL SBRM MDNKJ HK LAB JRIKW EGABTB DP LAHKJE, XNL ELHCC VNHLB IK IKGHBKL LBZL. TIWB CDKJ XBPDRB MDNR BIRCM AIHRCBEE EFIGB THGB CHSBW HK UAIL HE KDU QHTXIXUB.

> JDDW CNGO EFBGHIC IJBKL, HL'E IK ADKDR UDROHKJ XBEHWBE MDN IJIHK.

> H UDNCW EIM, CHSB CDKJ IKW FRDEFBR, XNL JHSBK MDNR CHPBEFIK...

> CHSB PIEL IKW WHB MDNKJ!

> FIEEUDRW

> Y!PVU'BN7HLK!SZ,GT'VU!RB'HR,YC!W

### 2. Substitution key
I pasted the first paragraph and part of the second paragraph into the substitution cipher solver at https://www.boxentriq.com/code-breaking/cryptogram to try and find the substitution key. The first result was readable, so I began with the cipher key for that result:

> hello special agent. it's nice to see you again. thanks for saving my life earlier this year, that was quite the adventure. ever since getting off your planet, i've missed this place greatly, even though your kind can be cruel, strange and violent, it provides a wonderful home filled with hope for the future.

This also helped helped with determining which characters represented commas, periods and apostrophes.

Key for my new cipher from boxentriq:

> HELOSPCIAGNTYUKFZRVMWQDBJX


The original cipher also had an additional 8 characters that first appeared in the fourth paragraph. I wasn't sure if they were numbers or other punctuation (or possibly something else). I assigned each of them numbers for the time being with the intention to examine them more closely while translating the text paragraph-by-paragraph. 


### 3. Editing and translating

I had made a few mistakes when I first transposed the code. I used the substitute operation on CyberChef with the key I found using boxentriq to translate each paragraph and fix the typos I found by comparing the original text with my key.

Through this process, I noticed a few errors in the cipher key. I adjusted the key as I deciphered the text. The key in step 2 is the final key I used to translate the text, and the cipher in step 1 is likewise the final edited version. "councel" is misspelled in the translated text, but after triple-checking the cipher key and translation, it appears that Klumgongyn simply made a typo. Happens to the best of us.

The 8 additional characters did seem to be numbers (six separate digits) and an exclamation mark. I left the numbers as they were since they weren't in the password.

The fully translated text:


> HELLO SPECIAL AGENT, IT'S NICE TO SEE YOU AGAIN. THANKS FOR SAVING MY LIFE EARLIER THIS YEAR. THAT WAS QUITE THE ADVENTURE. EVER SINCE GETTING OFF YOUR PLANET I'VE MISSED THIS PLACE GREATLY. EVEN THOUGH YOUR KIND CAN BE CRUEL, STRANGE AND VIOLENT IT PROVIDES A WONDERFUL HOME FILLED WITH HOPE FOR THE FUTURE.

> IT IS THEREFORE THAT I'VE DECIDED TO JOIN YOUR PLANET OF HAIRLESS APES. AFTER CONSULTING WITH THE OVERSEER, WE HAVE REACHED AN AGREEMENT THAT I WILL BECOME YOUR NEW COUNCEL LEADER, MEANING THERE IS NOW A DIRECT LINK BETWEEN THE KLUMGONS AND EARTHLINGS MAKING BOTH OUR POSITIONS IN THE GALAXIES MUCH STRONGER. MOSTLY YOURS, SINCE WE ARE ABSOLUTE LIGHTYEARS AHEAD OF YOUR STEAMPUNK TECHNOLOGY AND "MICRO" CHIPS.

> I AM ALSO PLEASED TO LEARN THAT YOU ARE STILL THE TOP SPECIAL AGENT. THIS TASK IS DESIGNED TO IDENTIFY IF YOU ARE TRULY "THE ONE". UPON COMPLETION YOU SHALL RECEIVE THE FILES TO USE THE ANCIENT KLUMGON LANGUAGE. IT WAS WRITTEN BY XYNTOLYR, ONE OF THE FIRST ELDERS OF OUR ONLY TRIBE AT THE TIME.

> OUR LANGUAGE WAS FOUNDED 123456 YEARS AGO! THIS MAKES IT VERY YOUNG IN THE GRAND SCHEME OF THINGS, BUT STILL QUITE AN ANCIENT TEXT. MADE LONG BEFORE YOUR EARLY HAIRLESS SPACE MICE LIVED IN WHAT IS NOW ZIMBABWE.

> GOOD LUCK SPECIAL AGENT, IT'S AN HONOR WORKING BESIDES YOU AGAIN.

> I WOULD SAY, LIVE LONG AND PROSPER, BUT GIVEN YOUR LIFESPAN...

> LIVE FAST AND DIE YOUNG!

> PASSWORD

> J!FQW'EU!ITN!VX,CM'QW!RE'IR,JL!D

The password didn't work initially, so I tried using all lowercase letters instead. This gave me the correct password:

> j!fqw'eu!itn!vx,cm'qw!re'ir,jl!d
