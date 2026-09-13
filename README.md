# Exercise Ball Size Finder

A tiny, dependency-free calculator that tells you which exercise ball diameter to buy for your
height, and — the part most guides skip — the wall-tape mark to inflate it to.

**[Live demo](https://ballholder.github.io/exercise-ball-size-finder/)**

## Why this exists

Almost every exercise ball size chart stops at "you are 5'7", buy a 65 cm". Two things go wrong after
that:

1. **Use case changes the answer.** A ball compresses 3 to 5 cm under sustained sitting, so the ball
   that fits you for planks is often one size too small under a desk. Birthing balls want your hips
   slightly above your knees rather than level. This tool adjusts for both.
2. **Nobody inflates to the right size.** A "65 cm" ball measures 65 cm only when fully inflated, and
   most people stop pumping at 60 or 61 cm because it already feels firm. An under-inflated 65
   behaves like a 55. The tool gives you a height to tape on the wall and pump to.

## Usage

One file, no build step, no dependencies. Open `index.html`, or drop it in an iframe:

```html
<iframe src="https://ballholder.github.io/exercise-ball-size-finder/"
        width="100%" height="1100" style="border:0" title="Exercise Ball Size Finder"></iframe>
```

## Sizing bands

| Ball | Height | Inflated diameter | Typical use |
|---|---|---|---|
| 45 cm | Under 5'1" (under 155 cm) | 17.7 in | Kids, petite adults |
| 55 cm | 5'1" – 5'6" (155 – 167 cm) | 21.7 in | Most women, physio |
| 65 cm | 5'6" – 6'0" (168 – 184 cm) | 25.6 in | Most men, the gym standard |
| 75 cm | 6'1" – 6'7" (185 – 202 cm) | 29.5 in | Tall users, birthing, desk chairs |
| 85 cm | 6'8" and up (203 cm+) | 33.5 in | Very tall users |

These bands match the charts published by the major manufacturers. Leg length, ball firmness and
body weight all shift how you actually sit, so treat the number as a starting point and confirm it
with the sit test built into the tool.

## Full version

This is a trimmed-down version. The full
[Exercise Ball Size Finder](https://ballholder.com/exercise-ball-size-finder/) adds a to-scale
side-view figure of a person your height sitting on the ball, a tappable size ladder for comparing
against a ball you already own, and burst-rating guidance by body weight.

## Contributing

Corrections to the sizing bands are welcome, especially sourced ones — open an issue or a PR.

## License

MIT
