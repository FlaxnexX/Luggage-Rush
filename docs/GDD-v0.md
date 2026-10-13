# Luggage Rush

**GDD v0 · Mete Eren Çelik · 2400005227 · https://github.com/FlaxnexX/Luggage-Rush  · 13 October 2026**

## 1.Pitch

As an airport worker, drag and toss incoming luggage from a moving conveyor belt into matching cargo carts while ignoring forbidden fragile items before the area overflows.

## 2.Core loop

- **The verb:** Toss — Click and drag a luggage piece with the mouse to fling it into the correct cargo cart.
- **What makes it harder:** The conveyor belt speed increases by 10% every 20 seconds. Also, random non-luggage items like computer monitors appear on the belt; throwing them into carts gives a -50 score penalty.
- **What makes it satisfying:** A crisp hit sound and +100 score popup on every right toss, plus a combo counter that gives bonus points after 5 correct throws in a row.
- **How it ends:** Win by loading 40 correct bags within 90 seconds; fail if 3 bags fall off the belt or if you throw 2 wrong fragile items into the carts (win and fail values are baseline targets and will be balanced during playtesting).
- **Modes or difficulty (if any):** Normal Shift mode has a standard belt speed, while Rush Hour mode starts the belt 30% faster and spawns forbidden items more often.

## 3.Flavor

2D top-down view built with the Unity 6 LTS 2D template.

## 4.List of Three Games

1. **Wilmot's Warehouse** (Hollow Ponds, 2019) — take: Fast visual sorting and category matching under time pressure / cut: Tile-based grid movement and long-term storage planning.
2. **Conveyor Chaos** (Retro arcade style games) — take: Moving conveyor belt that speeds up over time and forces quick decisions / cut: Factory machinery hazards and multi-room layouts.
3. **Fruit Ninja** (Halfbrick Studios, 2010) — take: Bombs and trap objects (like monitors here) that spawn randomly to punish blind clicking / cut: Swipe slicing mechanics and multiple combo blades.
