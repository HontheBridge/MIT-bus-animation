{\rtf1\ansi\ansicpg1252\cocoartf2636
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\froman\fcharset0 TimesNewRomanPSMT;\f1\froman\fcharset0 TimesNewRomanPS-BoldMT;\f2\fnil\fcharset0 LucidaGrande;
}
{\colortbl;\red255\green255\blue255;\red27\green31\blue35;\red255\green255\blue255;}
{\*\expandedcolortbl;;\cssrgb\c14118\c16078\c18431;\cssrgb\c100000\c100000\c100000;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid101\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{hyphen\}}{\leveltext\leveltemplateid102\'01\uc0\u8259 ;}{\levelnumbers;}\fi-360\li1440\lin1440 }{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{hyphen\}}{\leveltext\leveltemplateid103\'01\uc0\u8259 ;}{\levelnumbers;}\fi-360\li2160\lin2160 }{\listname ;}\listid2}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}}
\margl1440\margr1440\vieww24820\viewh16000\viewkind0
\deftab720
\pard\pardeftab720\sa320\partightenfactor0

\f0\fs36 \cf2 \cb3 \expnd0\expndtw0\kerning0
Map Animation and Bus Tracker\
Exercise for Week 9 - MIT Emeritus Online Course\
\pard\pardeftab720\sa320\partightenfactor0

\f1\b \cf2 Introduction:
\f0\b0  In this project we used MapBox API along with the display an interactive map of the Cambridge, MA area and demonstrate the movement of a bus from MIT\'92s campus to Harvards.\

\f1\b How to run: 
\f0\b0 Once open in browser, click the button in the top-left corner.  Refresh page to repeat.\

\f1\b Support:
\f0\b0  For support, please reach out to me directly over GitHub ('HonTheBridge') or over social media @MrJohnnyJohnson\

\f1\b Roadmap: 
\f0\b0 Future features and add-ons may include the following: \
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320\partightenfactor0
\ls1\ilvl0\cf2 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}Additional bus routes\
{\listtext	\uc0\u8226 	}real-time tracking through MBTA API data\
{\listtext	\uc0\u8226 	}Ability to select specific routes\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320\partightenfactor0
\ls1\ilvl0\cf2 {\listtext	\uc0\u8226 	}Mapbox tilesets for topographic and night modes\
{\listtext	\uc0\u8226 	}Embed option\
\pard\tx720\pardeftab720\sa320\partightenfactor0
\cf2 \expnd0\expndtw0\kerning0
\

\f1\b Refactoring Additions:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa320\partightenfactor0
\ls2\ilvl0
\f0\b0 \cf2 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\ul mapboxgl.NavigationControl\ulnone \
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440\sa320\partightenfactor0
\ls2\ilvl1\cf2 {\listtext	
\f2 \uc0\u8259 
\f0 	}visualizePitch: true,\
{\listtext	
\f2 \uc0\u8259 
\f0 	}showZoom: true,\
{\listtext	
\f2 \uc0\u8259 
\f0 	}showCompass: true,\
\pard\tx220\tx720\tx1440\pardeftab720\li720\fi-720\sa320\partightenfactor0
\ls2\ilvl0\cf2 {\listtext	\uc0\u8226 	}\ul mapboxgl.Marker\ulnone \
\pard\tx940\tx1440\pardeftab720\li1440\fi-1440\sa320\partightenfactor0
\ls2\ilvl1\cf2 {\listtext	
\f2 \uc0\u8259 
\f0 	}formatting\
\pard\tx1660\tx2160\pardeftab720\li2160\fi-2160\sa320\partightenfactor0
\ls2\ilvl2\cf2 {\listtext	
\f2 \uc0\u8259 
\f0 	}color: red\
\pard\tx1660\tx2160\tx2880\pardeftab720\li2160\fi-2160\sa320\partightenfactor0
\ls2\ilvl2\cf2 {\listtext	
\f2 \uc0\u8259 
\f0 	}draggable: true,\expnd0\expndtw0\kerning0
\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardeftab720\pardirnatural\partightenfactor0
\cf0 \cb1 \kerning1\expnd0\expndtw0 LICENSE\
\pard\pardeftab720\sa320\partightenfactor0
\cf2 \cb3 \expnd0\expndtw0\kerning0
MIT License\cf2 \cb1 \
\pard\pardeftab720\partightenfactor0
\cf2 Copyright (c) 2021 Gabriel Hern\'e1ndez\
\
\pard\pardeftab720\qr\partightenfactor0
\cf2 \
\pard\pardeftab720\partightenfactor0
\cf2 Permission is hereby granted, free of charge, to any person obtaining a copy\
\pard\pardeftab720\qr\partightenfactor0
\cf2 \
\pard\pardeftab720\partightenfactor0
\cf2 of this software and associated documentation files (the "Software"), to deal\
\pard\pardeftab720\qr\partightenfactor0
\cf2 \
\pard\pardeftab720\partightenfactor0
\cf2 in the Software without restriction, including without limitation the rights\
\pard\pardeftab720\qr\partightenfactor0
\cf2 \
\pard\pardeftab720\partightenfactor0
\cf2 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell\
\pard\pardeftab720\qr\partightenfactor0
\cf2 \
\pard\pardeftab720\partightenfactor0
\cf2 copies of the Software, and to permit persons to whom the Software is\
\pard\pardeftab720\qr\partightenfactor0
\cf2 \
\pard\pardeftab720\partightenfactor0
\cf2 furnished to do so, subject to the following conditions:\
\
\pard\pardeftab720\qr\partightenfactor0
\cf2 \
\pard\pardeftab720\partightenfactor0
\cf2 The above copyright notice and this permission notice shall be included in all\
\pard\pardeftab720\qr\partightenfactor0
\cf2 \
\pard\pardeftab720\partightenfactor0
\cf2 copies or substantial portions of the Software.\
\
\pard\pardeftab720\qr\partightenfactor0
\cf2 \
\pard\pardeftab720\partightenfactor0
\cf2 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR\
\pard\pardeftab720\qr\partightenfactor0
\cf2 \
\pard\pardeftab720\partightenfactor0
\cf2 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,\
\pard\pardeftab720\qr\partightenfactor0
\cf2 \
\pard\pardeftab720\partightenfactor0
\cf2 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE\
\pard\pardeftab720\qr\partightenfactor0
\cf2 \
\pard\pardeftab720\partightenfactor0
\cf2 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER\
\pard\pardeftab720\qr\partightenfactor0
\cf2 \
\pard\pardeftab720\partightenfactor0
\cf2 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,\
\pard\pardeftab720\qr\partightenfactor0
\cf2 \
\pard\pardeftab720\partightenfactor0
\cf2 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE\
\pard\pardeftab720\qr\partightenfactor0
\cf2 \
\pard\pardeftab720\partightenfactor0
\cf2 SOFTWARE.\cf2 \cb3 \
}