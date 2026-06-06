# Design

## Direction
整体院の新規集客LP。高価格帯のデンタル/自費診療クリニックに近い静かな上質さを狙う。温かみのあるオフホワイトを基調に、彩度を抑えたネイビーで専門性、控えめなブラス（くすんだ金）を線・小見出しのアクセントに限定する。装飾は薄い罫線と余白で構成し、影・グラデーション・ガラス効果は最小限。添付写真を主役にする。チラシ風の煽り、過剰な発光グラデ、筆記体ラベルなどの「テンプレ感・AI感」を避ける。

## Palette
Paper: oklch(98.6% 0.004 85)  /* 温かいオフホワイト */
Surface: oklch(96.4% 0.006 85)
Ink: oklch(27% 0.018 255)
Muted: oklch(49% 0.02 255)
Navy: oklch(34% 0.04 255)
Navy Deep: oklch(24% 0.04 255)
Accent (Brass): oklch(60% 0.05 72)  /* 彩度を落とした金 */
Sage: oklch(56% 0.045 150)
Line: oklch(89% 0.008 85)

## Typography
Shippori Mincho B1 is the single typeface, used for Japanese body and headings to preserve trust and calm authority. Headings use weight 700 with generous letter-spacing (0.04em) and tall line-height for an airy, premium rhythm.
English captions are set as small uppercase Latin labels with wide tracking (no cursive/display fonts), keeping them quiet and editorial rather than decorative.
The brand monogram is a plain serif glyph inside a thin ring, so it does not compete with Japanese text.

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
