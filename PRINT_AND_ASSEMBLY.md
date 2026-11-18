# Starship S24/B7 print and assembly guide

This model is about 38 inches tall and is split into parts for the Markforged X7. The design has not been sliced in Eiger or physically assembled. The joints and stand need testing before the model can be displayed.

## Printing

1. Import the STLs into Eiger in millimeters. Many files retain assembly coordinates, so move and orient each part on the build plate. Separate the two solids in `upper_seam_keys_pair.stl` and position them individually for slicing.
2. Check the slice, raft and supports against your printer's build volume. Markforged lists 330 × 270 × 200 mm for the [X7 Gen 2](https://www-objects.markforged.com/craft/3d_printers_detail/x7/F-PR-3012.pdf).
3. Select Onyx as the base material. Start with Eiger's Onyx settings and choose the layer height and infill for the part. Continuous fiber is optional.
4. Make a small pin-and-socket fit coupon, or print one fin and its mating booster section first. Test the fit before printing the full stack.
5. Check support access around the engine nozzles and inside the joined lower booster. Clean and dry-fit the parts before bonding.

## Assembly

1. Sort the parts by folder. Filenames with `black` and `metal` identify the intended exterior finish.
2. Stack the booster sections in this order, from bottom to top: `booster_base_and_engines`, `lower_top`, `upper_bottom`, `upper_top`. The bottom section includes the engine cluster.
3. Pair each black flap half with its matching metal half. The halves need to be joined to each other and kept together during fitting; the attachment method has not been tested. The modeled aft-flap wires go in before the upper body section. The forward wires enter through the nose base before the nose joins the upper tank. Wire size and retention are not established.
4. Dry-fit the ship shells, nose, ship engines and booster connector. Use the keys and covers at their matching seams. The three bored booster keys align sections but do not provide axial retention.
5. Fit the four grid fins to the upper booster. Their retention hardware has not been established. The stand uses a hub, four legs, a rear post, two front clamps, two shelves and three spacers; its attachment to the booster still needs to be resolved.

## Part quantities

Paths are relative to `model/`. `upper_seam_keys_pair.stl` contains two pieces in one file.

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
| `03_joints/nose_bored_key.stl` | 1 |
| `03_joints/booster_bored_long_key.stl` | 3 |
| `03_joints/upper_seam_keys_pair.stl` | 1 |
| `04_stand/hub.stl` | 1 |
| `04_stand/leg.stl` | 4 |
| `04_stand/rear_post.stl` | 1 |
| `04_stand/front_clamp.stl` | 2 |
| `04_stand/shelf_front.stl` | 1 |
| `04_stand/shelf_back.stl` | 1 |
| `04_stand/spacer.stl` | 3 |
| `05_covers/cover_black_lower.stl` | 1 |
| `05_covers/cover_black_upper.stl` | 1 |
| `05_covers/cover_metal_lower.stl` | 1 |
| `05_covers/cover_metal_upper.stl` | 1 |
| `05_covers/nose_cover_black.stl` | 1 |
| `05_covers/nose_cover_metal.stl` | 1 |
