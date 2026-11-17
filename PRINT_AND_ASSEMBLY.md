# Starship S24/B7: print and assembly guide

This is a 38-inch model split into parts for the Markforged X7. The design is a work in progress: it has not been sliced in Eiger or physically assembled. Joint retention, hardware, support removal and stand stability still need testing.

## Printing

1. Import the STL files into Eiger in millimeters. They retain assembly coordinates, so place and orient each part on the build plate before slicing.
2. Check each part with its raft and supports against your printer's build volume. Markforged lists 330 × 270 × 200 mm for the X7 Gen 2; confirm the limits and settings for your machine in Eiger.
3. Use Onyx as the base material. Continuous fiber is optional reinforcement and requires compatible geometry and Eiger settings; it is not a replacement for the base material.
4. Start with a small fit test before printing the full stack. Check seams, flap pins and grid-fin pins for the fit your printer produces.
5. Review the slice layer by layer, particularly inside the joined lower booster and around its engine nozzles. Check that supports can be removed and that small features are retained. Eiger provides the material and time estimate for the selected settings.
6. Clean the parts and test-fit before bonding. Support contact can affect surface finish; choose orientations with visible surfaces in mind.

## Assembly overview

1. Sort the booster, ship, joints, stand and covers using the folders and quantities below. Names containing `black` and `metal` identify the two exterior finishes; they are not separate material requirements.
2. Arrange the booster sections from bottom to top: `booster_base_and_engines`, `lower_top`, `upper_bottom`, and `upper_top`. The lowest section and engine cluster are one part. The connection to the next section is not yet validated.
3. Pair each black flap half with its matching metal half. For the aft and forward flaps, the two halves were checked moving together; the method of joining them and retaining them on the body has not been tested.
4. Dry-fit the ship's lower and upper shell halves, nose halves, flap pairs and ship-engine part. Fit the connector between the ship and booster. The intended wire channels and stops are experimental; wire size, length, retention and installation have not been established.
5. Dry-fit the four grid fins on the upper booster. Their pins and proposed wire retention are experimental and have not been physically tested.
6. The stand files include a hub, four legs, a rear post, two front clamps, two shelves and three spacers. How the stand and lower booster are secured together, and whether they can safely support the complete stack, remain unverified.

Do not rely on the assembly as a freestanding display until the joints and stand have been tested. The CAD studies do not establish finished-part strength or fit.

## Part quantities

Paths are relative to `model/`. The seam-key pair file contains two pieces in one STL.

| File | Quantity |
| --- | ---: |
| `01_booster/booster_base_and_engines.stl` | 1 |
| `01_booster/lower_top.stl` | 1 |
| `01_booster/upper_bottom.stl` | 1 |
| `01_booster/upper_top.stl` | 1 |
| `01_booster/grid_fin.stl` | 4 |
| `02_ship/tank_bot_black.stl` | 1 |
| `02_ship/tank_top_black.stl` | 1 |
| `02_ship/tank_bot_metal.stl` | 1 |
| `02_ship/tank_top_metal.stl` | 1 |
| `02_ship/ss_cone_black_x1.stl` | 1 |
| `02_ship/ss_cone_metal_x1.stl` | 1 |
| `02_ship/ss_raptor_black_x1.stl` | 1 |
| `02_ship/flaps/flap_bot_right_black_x1.stl` | 1 |
| `02_ship/flaps/flap_top_left_metal_x1.stl` | 1 |
| `02_ship/flaps/flap_top_right_black_x1.stl` | 1 |
| `02_ship/flaps/flap_bot_left_metal_x1.stl` | 1 |
| `02_ship/flaps/flap_top_right_metal_x1.stl` | 1 |
| `02_ship/flaps/flap_top_left_black_x1.stl` | 1 |
| `02_ship/flaps/flap_bot_left_black_x1.stl` | 1 |
| `02_ship/flaps/flap_bot_right_metal_x1.stl` | 1 |
| `03_joints/long_key.stl` | 1 |
| `03_joints/ship_booster_connector.stl` | 1 |
| `03_joints/engine_connector.stl` | 1 |
| `04_stand/hub.stl` | 1 |
| `04_stand/leg.stl` | 4 |
| `04_stand/rear_post.stl` | 1 |
| `04_stand/front_clamp.stl` | 2 |
| `04_stand/shelf_front.stl` | 1 |
| `04_stand/shelf_back.stl` | 1 |
| `04_stand/spacer.stl` | 3 |
| `03_joints/nose_bored_key.stl` | 1 |
| `03_joints/booster_bored_long_key.stl` | 3 |
| `03_joints/upper_seam_keys_pair.stl` | 1 |
| `05_covers/cover_black_lower.stl` | 1 |
| `05_covers/cover_black_upper.stl` | 1 |
| `05_covers/cover_metal_lower.stl` | 1 |
| `05_covers/cover_metal_upper.stl` | 1 |
| `05_covers/nose_cover_black.stl` | 1 |
| `05_covers/nose_cover_metal.stl` | 1 |

## X7 reference

[Markforged X7 product specifications](https://www-objects.markforged.com/craft/3d_printers_detail/x7/F-PR-3012.pdf)
