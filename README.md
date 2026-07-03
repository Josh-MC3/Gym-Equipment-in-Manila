# Adding photos

Drop image files into this `images/` folder using the exact filenames below (JPG). If a file is missing, the page shows a clean fallback icon instead - nothing breaks.

Recommended: square-ish photos, at least 200x200px, under 300KB each (resize/compress before uploading so the page stays fast on mobile).

## Free weights & strength
| Filename | Item |
|---|---|
| `kettlebell-set.jpg` | Kettlebell set |
| `bumper-plates.jpg` | Bumper / iron plates |
| `olympic-barbell.jpg` | Olympic barbell |
| `adjustable-dumbbells.jpg` | Adjustable dumbbell set |
| `flat-bench.jpg` | Flat/adjustable bench |
| `squat-rack.jpg` | Squat rack / power rack |
| `fixed-barbells.jpg` | Pre-loaded fixed barbell set |

## Cardio machines
| Filename | Item |
|---|---|
| `treadmill.jpg` | Treadmill (commercial) |
| `elliptical.jpg` | Elliptical trainer |
| `spin-bike.jpg` | Stationary / spin bike |
| `stair-climber.jpg` | Stair climber |

## Strength machines
| Filename | Item |
|---|---|
| `cable-crossover.jpg` | Cable crossover / functional trainer |
| `lat-pulldown.jpg` | Lat pulldown / low row combo |
| `leg-press.jpg` | Leg press machine |
| `leg-extension-curl.jpg` | Leg extension / curl machine |
| `chest-press.jpg` | Chest press machine |
| `smith-machine.jpg` | Smith machine |

## Conditioning & functional
| Filename | Item |
|---|---|
| `rowing-machine.jpg` | Rowing machine |
| `air-bike.jpg` | Air bike / assault bike |
| `battle-rope.jpg` | Battle rope |
| `slam-balls.jpg` | Slam balls / medicine balls |
| `jump-ropes.jpg` | Jump ropes |
| `trx-trainer.jpg` | TRX suspension trainer |
| `foam-rollers.jpg` | Foam rollers |
| `stretch-mats.jpg` | Stretch / yoga mats |

## Flooring & rig
| Filename | Item |
|---|---|
| `rubber-flooring.jpg` | Interlocking rubber mats |
| `pull-up-rig.jpg` | Pull-up rig / frame |
| `plyo-boxes.jpg` | Plyo boxes |
| `cardio-flooring.jpg` | Cardio-zone flooring |

## Facility fixtures & fit-out
| Filename | Item |
|---|---|
| `wall-mirrors.jpg` | Wall mirrors |
| `led-light-fixture.jpg` | Overhead LED light fixture |
| `hvac-system.jpg` | HVAC / ventilation system |
| `sound-system.jpg` | Sound system |
| `cctv-system.jpg` | CCTV security camera system |
| `access-control.jpg` | Key fob / access control system |

## Amenities & front-of-house
| Filename | Item |
|---|---|
| `front-desk.jpg` | Front desk / reception counter |
| `lockers.jpg` | Lockers |
| `restroom-fixtures.jpg` | Restroom fixtures / renovation |
| `water-fountain.jpg` | Water fountain / filtered station |
| `hand-towels.jpg` | Hand towels |
| `wipe-down-station.jpg` | Equipment wipe-down station |
| `vending-machine.jpg` | Vending machine |

## Signage & wayfinding
| Filename | Item |
|---|---|
| `exit-signage.jpg` | Exit / emergency signage set |
| `wayfinding-signage.jpg` | Zone / wayfinding signage package |
| `instructional-posters.jpg` | Muscle-group instructional posters |
| `aed-unit.jpg` | AED unit + signage |

## Accessories & logistics
| Filename | Item |
|---|---|
| `resistance-bands.jpg` | Resistance band set |
| `agility-ladder.jpg` | Agility ladder + cones |
| `interval-timer.jpg` | Interval timer + speaker |
| `first-aid-kit.jpg` | First aid kit |

## Using a URL instead of a local file

You don't have to save files here at all. Open `index.html`, find the `DATA` array near the top of the `<script>` block, and change any `img` value from a bare name to a full link, e.g.:

```js
img: "kettlebell-set"
// becomes
img: "https://example.com/photos/my-kettlebells.jpg"
```

Both formats work side by side - mix local files and URLs however you like.
