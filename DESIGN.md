# Design

## Direction
整体院の新規集客LP。名古屋の歯科ブランド「RYO JIMBO DENTAL」系のような、明るく清潔でモダンなクリニックの雰囲気を目指す。白基調の広い余白に、フレッシュなティール（青緑）をブランドカラーとして用い、温かみのあるサンド系ニュートラルで柔らかさを添える。角丸を大きく取った丸みのあるカード、やわらかいシャドウ、ピル型のCTAで、清潔感・親しみ・信頼感を両立する。写真を主役にし、見出しはゴシック体の太字でモダンに。

## Palette
BG: oklch(99.2% 0.003 200)        /* 明るい白 */
Surface: oklch(97.3% 0.011 195)   /* 涼やかなサーフェス */
Surface Warm: oklch(96.8% 0.016 75) /* 温かいサンド */
Brand (Teal): oklch(61% 0.092 192)
Brand Deep: oklch(50% 0.09 198)
Brand Night: oklch(34% 0.058 214) /* 濃色セクション用ティール寄りネイビー */
Brand Soft: oklch(95% 0.035 190)  /* 淡いティールのタイント */
Accent (Warm): oklch(74% 0.11 62)
Ink: oklch(28% 0.025 235)
Muted: oklch(50% 0.022 235)
Line: oklch(91% 0.012 200)

## Typography
Noto Sans JP is the primary typeface for Japanese body and headings — a clean modern gothic that reads bright and approachable. Headings use weight 900 for a confident, contemporary presence; body uses 400 with tall line-height.
Jost (geometric sans) is used for small English captions, numbers, and the monogram, giving a crisp modern accent without competing with the Japanese text.
The brand monogram is a rounded teal-gradient tile.

## Components
Sticky header with primary reservation CTA.
Hero with image-led proof blocks.
Pain cards with line icons.
Comparison diagram for temporary relief versus root-cause care.
Reason cards with trust markers.
Flow timeline.
Testimonials and before-after examples marked as replaceable examples.
FAQ accordion.
Sticky mobile reservation bar.

## Motion
Subtle fade and slide reveals using IntersectionObserver.
Hover lift on CTA and cards.
No motion-critical content; all content is visible without JavaScript.
