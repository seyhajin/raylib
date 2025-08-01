## Building the Examples

The examples assume you have already built the `raylib` library in `../src`.

### With GNU make

- `make` builds all examples
- `make [module]` builds all examples for a particular module (e.g `make core`)

### With Zig

The [Zig](https://ziglang.org/) toolchain can compile `C` and `C++` in addition to `Zig`.
You may find it easier to use than other toolchains, especially when it comes to cross-compiling.

- `zig build` to compile all examples
- `zig build [module]` to compile all examples for a module (e.g. `zig build core`)
- `zig build [example]` to compile _and run_ a particular example (e.g. `zig build core_basic_window`)

## EXAMPLES LIST

### category: core

Examples using raylib core platform functionality like window creation, inputs, drawing modes and system functionality.

| ## | example  | image  | difficulty<br>level | version<br>created | last version<br>updated | original<br>developer |
|----|----------|--------|:-------------------:|:------------------:|:-----------------------:|:----------------------|
| 01 | [core_basic_window](core/core_basic_window.c) | <img src="core/core_basic_window.png" alt="core_basic_window" width="80"> | ⭐️☆☆☆ | 1.0 | 1.0 | [Ray](https://github.com/raysan5) |
| 02 | [core_input_keys](core/core_input_keys.c) | <img src="core/core_input_keys.png" alt="core_input_keys" width="80"> | ⭐️☆☆☆ | 1.0 | 1.0 | [Ray](https://github.com/raysan5) |
| 03 | [core_input_mouse](core/core_input_mouse.c) | <img src="core/core_input_mouse.png" alt="core_input_mouse" width="80"> | ⭐️☆☆☆ | 1.0 | 5.5 | [Ray](https://github.com/raysan5) |
| 04 | [core_input_mouse_wheel](core/core_input_mouse_wheel.c) | <img src="core/core_input_mouse_wheel.png" alt="core_input_mouse_wheel" width="80"> | ⭐️☆☆☆ | 1.1 | 1.3 | [Ray](https://github.com/raysan5) |
| 05 | [core_input_gamepad](core/core_input_gamepad.c) | <img src="core/core_input_gamepad.png" alt="core_input_gamepad" width="80"> | ⭐️☆☆☆ | 1.1 | 4.2 | [Ray](https://github.com/raysan5) |
| 06 | [core_input_multitouch](core/core_input_multitouch.c) | <img src="core/core_input_multitouch.png" alt="core_input_multitouch" width="80"> | ⭐️☆☆☆ | 2.1 | 2.5 | [Berni](https://github.com/Berni8k) |
| 07 | [core_input_gestures](core/core_input_gestures.c) | <img src="core/core_input_gestures.png" alt="core_input_gestures" width="80"> | ⭐️⭐️☆☆ | 1.4 | 4.2 | [Ray](https://github.com/raysan5) |
| 08 | [core_input_virtual_controls](core/core_input_virtual_controls.c) | <img src="core/core_input_virtual_controls.png" alt="core_input_virtual_controls" width="80"> | ⭐️⭐️☆☆ | 5.0 | 5.0 | [oblerion](https://github.com/oblerion) |
| 09 | [core_2d_camera](core/core_2d_camera.c) | <img src="core/core_2d_camera.png" alt="core_2d_camera" width="80"> | ⭐️⭐️☆☆ | 1.5 | 3.0 | [Ray](https://github.com/raysan5) |
| 10 | [core_2d_camera_mouse_zoom](core/core_2d_camera_mouse_zoom.c) | <img src="core/core_2d_camera_mouse_zoom.png" alt="core_2d_camera_mouse_zoom" width="80"> | ⭐️⭐️☆☆ | 4.2 | 4.2 | [Jeffery Myers](https://github.com/JeffM2501) |
| 11 | [core_2d_camera_platformer](core/core_2d_camera_platformer.c) | <img src="core/core_2d_camera_platformer.png" alt="core_2d_camera_platformer" width="80"> | ⭐️⭐️⭐️☆ | 2.5 | 3.0 | [arvyy](https://github.com/arvyy) |
| 12 | [core_2d_camera_split_screen](core/core_2d_camera_split_screen.c) | <img src="core/core_2d_camera_split_screen.png" alt="core_2d_camera_split_screen" width="80"> | ⭐️⭐️⭐️⭐️ | 4.5 | 4.5 | [Gabriel dos Santos Sanches](https://github.com/gabrielssanches) |
| 13 | [core_3d_camera_mode](core/core_3d_camera_mode.c) | <img src="core/core_3d_camera_mode.png" alt="core_3d_camera_mode" width="80"> | ⭐️☆☆☆ | 1.0 | 1.0 | [Ray](https://github.com/raysan5) |
| 14 | [core_3d_camera_free](core/core_3d_camera_free.c) | <img src="core/core_3d_camera_free.png" alt="core_3d_camera_free" width="80"> | ⭐️☆☆☆ | 1.3 | 1.3 | [Ray](https://github.com/raysan5) |
| 15 | [core_3d_camera_first_person](core/core_3d_camera_first_person.c) | <img src="core/core_3d_camera_first_person.png" alt="core_3d_camera_first_person" width="80"> | ⭐️⭐️☆☆ | 1.3 | 1.3 | [Ray](https://github.com/raysan5) |
| 16 | [core_3d_camera_split_screen](core/core_3d_camera_split_screen.c) | <img src="core/core_3d_camera_split_screen.png" alt="core_3d_camera_split_screen" width="80"> | ⭐️⭐️⭐️☆ | 3.7 | 4.0 | [Jeffery Myers](https://github.com/JeffM2501) |
| 17 | [core_3d_picking](core/core_3d_picking.c) | <img src="core/core_3d_picking.png" alt="core_3d_picking" width="80"> | ⭐️⭐️☆☆ | 1.3 | 4.0 | [Ray](https://github.com/raysan5) |
| 18 | [core_world_screen](core/core_world_screen.c) | <img src="core/core_world_screen.png" alt="core_world_screen" width="80"> | ⭐️⭐️☆☆ | 1.3 | 1.4 | [Ray](https://github.com/raysan5) |
| 19 | [core_custom_logging](core/core_custom_logging.c) | <img src="core/core_custom_logging.png" alt="core_custom_logging" width="80"> | ⭐️⭐️⭐️☆ | 2.5 | 2.5 | [Pablo Marcos Oltra](https://github.com/pamarcos) |
| 20 | [core_window_flags](core/core_window_flags.c) | <img src="core/core_window_flags.png" alt="core_window_flags" width="80"> | ⭐️⭐️⭐️☆ | 3.5 | 3.5 | [Ray](https://github.com/raysan5) |
| 21 | [core_window_letterbox](core/core_window_letterbox.c) | <img src="core/core_window_letterbox.png" alt="core_window_letterbox" width="80"> | ⭐️⭐️☆☆ | 2.5 | 4.0 | [Anata](https://github.com/anatagawa) |
| 22 | [core_window_should_close](core/core_window_should_close.c) | <img src="core/core_window_should_close.png" alt="core_window_should_close" width="80"> | ⭐️☆☆☆ | 4.2 | 4.2 | [Ray](https://github.com/raysan5) |
| 23 | [core_drop_files](core/core_drop_files.c) | <img src="core/core_drop_files.png" alt="core_drop_files" width="80"> | ⭐️⭐️☆☆ | 1.3 | 4.2 | [Ray](https://github.com/raysan5) |
| 24 | [core_random_values](core/core_random_values.c) | <img src="core/core_random_values.png" alt="core_random_values" width="80"> | ⭐️☆☆☆ | 1.1 | 1.1 | [Ray](https://github.com/raysan5) |
| 25 | [core_storage_values](core/core_storage_values.c) | <img src="core/core_storage_values.png" alt="core_storage_values" width="80"> | ⭐️⭐️☆☆ | 1.4 | 4.2 | [Ray](https://github.com/raysan5) |
| 26 | [core_vr_simulator](core/core_vr_simulator.c) | <img src="core/core_vr_simulator.png" alt="core_vr_simulator" width="80"> | ⭐️⭐️⭐️☆ | 2.5 | 4.0 | [Ray](https://github.com/raysan5) |
| 27 | [core_loading_thread](core/core_loading_thread.c) | <img src="core/core_loading_thread.png" alt="core_loading_thread" width="80"> | ⭐️⭐️⭐️☆ | 2.5 | 3.0 | [Ray](https://github.com/raysan5) |
| 28 | [core_scissor_test](core/core_scissor_test.c) | <img src="core/core_scissor_test.png" alt="core_scissor_test" width="80"> | ⭐️☆☆☆ | 2.5 | 3.0 | [Chris Dill](https://github.com/MysteriousSpace) |
| 29 | [core_basic_screen_manager](core/core_basic_screen_manager.c) | <img src="core/core_basic_screen_manager.png" alt="core_basic_screen_manager" width="80"> | ⭐️☆☆☆ | 4.0 | 4.0 | [Ray](https://github.com/raysan5) |
| 30 | [core_custom_frame_control](core/core_custom_frame_control.c) | <img src="core/core_custom_frame_control.png" alt="core_custom_frame_control" width="80"> | ⭐️⭐️⭐️⭐️ | 4.0 | 4.0 | [Ray](https://github.com/raysan5) |
| 31 | [core_smooth_pixelperfect](core/core_smooth_pixelperfect.c) | <img src="core/core_smooth_pixelperfect.png" alt="core_smooth_pixelperfect" width="80"> | ⭐️⭐️⭐️☆ | 3.7 | 4.0 | [Giancamillo Alessandroni](https://github.com/NotManyIdeasDev) |
| 32 | [core_random_sequence](core/core_random_sequence.c) | <img src="core/core_random_sequence.png" alt="core_random_sequence" width="80"> | ⭐️☆☆☆ | 5.0 | 5.0 | [Dalton Overmyer](https://github.com/REDl3east) |
| 33 | [core_basic_window_web](core/core_basic_window_web.c) | <img src="core/core_basic_window_web.png" alt="core_basic_window_web" width="80"> | ⭐️☆☆☆ | 1.3 | 1.3 | [Ray](https://github.com/raysan5) |
| 34 | [core_input_gestures_web](core/core_input_gestures_web.c) | <img src="core/core_input_gestures_web.png" alt="core_input_gestures_web" width="80"> | ⭐️⭐️☆☆ | 4.6-dev | 4.6-dev | [ubkp](https://github.com/ubkp) |
| 35 | [core_automation_events](core/core_automation_events.c) | <img src="core/core_automation_events.png" alt="core_automation_events" width="80"> | ⭐️⭐️⭐️☆ | 5.0 | 5.0 | [Ray](https://github.com/raysan5) |
| 36 | [core_high_dpi](core/core_high_dpi.c) | <img src="core/core_high_dpi.png" alt="core_high_dpi" width="80"> | ⭐️☆☆☆ | 5.0 | 5.0 | [Jonathan Marler](https://github.com/marler8997) |

### category: shapes

Examples using raylib shapes drawing functionality, provided by raylib [shapes](../src/shapes.c) module.

| ## | example  | image  | difficulty<br>level | version<br>created | last version<br>updated | original<br>developer |
|----|----------|--------|:-------------------:|:------------------:|:-----------------------:|:----------------------|
| 36 | [shapes_basic_shapes](shapes/shapes_basic_shapes.c) | <img src="shapes/shapes_basic_shapes.png" alt="shapes_basic_shapes" width="80"> | ⭐️☆☆☆ | 1.0 | 4.2 | [Ray](https://github.com/raysan5) |
| 37 | [shapes_bouncing_ball](shapes/shapes_bouncing_ball.c) | <img src="shapes/shapes_bouncing_ball.png" alt="shapes_bouncing_ball" width="80"> | ⭐️☆☆☆ | 2.5 | 2.5 | [Ray](https://github.com/raysan5) |
| 38 | [shapes_colors_palette](shapes/shapes_colors_palette.c) | <img src="shapes/shapes_colors_palette.png" alt="shapes_colors_palette" width="80"> | ⭐️⭐️☆☆ | 1.0 | 2.5 | [Ray](https://github.com/raysan5) |
| 39 | [shapes_logo_raylib](shapes/shapes_logo_raylib.c) | <img src="shapes/shapes_logo_raylib.png" alt="shapes_logo_raylib" width="80"> | ⭐️☆☆☆ | 1.0 | 1.0 | [Ray](https://github.com/raysan5) |
| 40 | [shapes_logo_raylib_anim](shapes/shapes_logo_raylib_anim.c) | <img src="shapes/shapes_logo_raylib_anim.png" alt="shapes_logo_raylib_anim" width="80"> | ⭐️⭐️☆☆ | 2.5 | 4.0 | [Ray](https://github.com/raysan5) |
| 41 | [shapes_rectangle_scaling](shapes/shapes_rectangle_scaling.c) | <img src="shapes/shapes_rectangle_scaling.png" alt="shapes_rectangle_scaling" width="80"> | ⭐️⭐️☆☆ | 2.5 | 2.5 | [Vlad Adrian](https://github.com/demizdor) |
| 42 | [shapes_lines_bezier](shapes/shapes_lines_bezier.c) | <img src="shapes/shapes_lines_bezier.png" alt="shapes_lines_bezier" width="80"> | ⭐️☆☆☆ | 1.7 | 1.7 | [Ray](https://github.com/raysan5) |
| 43 | [shapes_collision_area](shapes/shapes_collision_area.c) | <img src="shapes/shapes_collision_area.png" alt="shapes_collision_area" width="80"> | ⭐️⭐️☆☆ | 2.5 | 2.5 | [Ray](https://github.com/raysan5) |
| 44 | [shapes_following_eyes](shapes/shapes_following_eyes.c) | <img src="shapes/shapes_following_eyes.png" alt="shapes_following_eyes" width="80"> | ⭐️⭐️☆☆ | 2.5 | 2.5 | [Ray](https://github.com/raysan5) |
| 45 | [shapes_easings_ball_anim](shapes/shapes_easings_ball_anim.c) | <img src="shapes/shapes_easings_ball_anim.png" alt="shapes_easings_ball_anim" width="80"> | ⭐️⭐️☆☆ | 2.5 | 2.5 | [Ray](https://github.com/raysan5) |
| 46 | [shapes_easings_box_anim](shapes/shapes_easings_box_anim.c) | <img src="shapes/shapes_easings_box_anim.png" alt="shapes_easings_box_anim" width="80"> | ⭐️⭐️☆☆ | 2.5 | 2.5 | [Ray](https://github.com/raysan5) |
| 47 | [shapes_easings_rectangle_array](shapes/shapes_easings_rectangle_array.c) | <img src="shapes/shapes_easings_rectangle_array.png" alt="shapes_easings_rectangle_array" width="80"> | ⭐️⭐️⭐️☆ | 2.0 | 2.5 | [Ray](https://github.com/raysan5) |
| 48 | [shapes_draw_ring](shapes/shapes_draw_ring.c) | <img src="shapes/shapes_draw_ring.png" alt="shapes_draw_ring" width="80"> | ⭐️⭐️⭐️☆ | 2.5 | 2.5 | [Vlad Adrian](https://github.com/demizdor) |
| 49 | [shapes_draw_circle_sector](shapes/shapes_draw_circle_sector.c) | <img src="shapes/shapes_draw_circle_sector.png" alt="shapes_draw_circle_sector" width="80"> | ⭐️⭐️⭐️☆ | 2.5 | 2.5 | [Vlad Adrian](https://github.com/demizdor) |
| 50 | [shapes_draw_rectangle_rounded](shapes/shapes_draw_rectangle_rounded.c) | <img src="shapes/shapes_draw_rectangle_rounded.png" alt="shapes_draw_rectangle_rounded" width="80"> | ⭐️⭐️⭐️☆ | 2.5 | 2.5 | [Vlad Adrian](https://github.com/demizdor) |
| 51 | [shapes_top_down_lights](shapes/shapes_top_down_lights.c) | <img src="shapes/shapes_top_down_lights.png" alt="shapes_top_down_lights" width="80"> | ⭐️⭐️⭐️⭐️ | 4.2 | 4.2 | [Jeffery Myers](https://github.com/JeffM2501) |
| 52 | [shapes_rectangle_advanced](shapes/shapes_rectangle_advanced.c) | <img src="shapes/shapes_rectangle_advanced.png" alt="shapes_rectangle_advanced" width="80"> | ⭐️⭐️⭐️⭐️ | 5.5 | 5.5 | [Everton Jr.](https://github.com/evertonse) |
| 53 | [shapes_splines_drawing](shapes/shapes_splines_drawing.c) | <img src="shapes/shapes_splines_drawing.png" alt="shapes_splines_drawing" width="80"> | ⭐️⭐️⭐️☆ | 5.0 | 5.0 | [Ray](https://github.com/raysan5) |
| 54 | [shapes_digital_clock](shapes/shapes_digital_clock.c) | <img src="shapes/shapes_digital_clock.png" alt="shapes_digital_clock" width="80"> | ⭐️⭐️☆☆ | 5.5 | 5.5 | [Hamza RAHAL](https://github.com/rhmz-rhl) |
| 55 | [shapes_double_pendulum](shapes/shapes_double_pendulum.c) | <img src="shapes/shapes_double_pendulum.png" alt="shapes_double_pendulum" width="80"> | ⭐️⭐️☆☆ | 5.5 | 5.5 | [JoeCheong](https://github.com/Joecheong2006) |
### category: textures

Examples using raylib textures functionality, including image/textures loading/generation and drawing, provided by raylib [textures](../src/textures.c) modul

| ## | example  | image  | difficulty<br>level | version<br>created | last version<br>updated | original<br>developer |
|----|----------|--------|:-------------------:|:------------------:|:-----------------------:|:----------------------|
| 56 | [textures_logo_raylib](textures/textures_logo_raylib.c) | <img src="textures/textures_logo_raylib.png" alt="textures_logo_raylib" width="80"> | ⭐️☆☆☆ | 1.0 | 1.0 | [Ray](https://github.com/raysan5) |
| 57 | [textures_srcrec_dstrec](textures/textures_srcrec_dstrec.c) | <img src="textures/textures_srcrec_dstrec.png" alt="textures_srcrec_dstrec" width="80"> | ⭐️⭐️⭐️☆ | 1.3 | 1.3 | [Ray](https://github.com/raysan5) |
| 58 | [textures_image_drawing](textures/textures_image_drawing.c) | <img src="textures/textures_image_drawing.png" alt="textures_image_drawing" width="80"> | ⭐️⭐️☆☆ | 1.4 | 1.4 | [Ray](https://github.com/raysan5) |
| 59 | [textures_image_generation](textures/textures_image_generation.c) | <img src="textures/textures_image_generation.png" alt="textures_image_generation" width="80"> | ⭐️⭐️☆☆ | 1.8 | 1.8 | [Wilhem Barbier](https://github.com/nounoursheureux) |
| 60 | [textures_image_loading](textures/textures_image_loading.c) | <img src="textures/textures_image_loading.png" alt="textures_image_loading" width="80"> | ⭐️☆☆☆ | 1.3 | 1.3 | [Ray](https://github.com/raysan5) |
| 61 | [textures_image_processing](textures/textures_image_processing.c) | <img src="textures/textures_image_processing.png" alt="textures_image_processing" width="80"> | ⭐️⭐️⭐️☆ | 1.4 | 3.5 | [Ray](https://github.com/raysan5) |
| 62 | [textures_image_text](textures/textures_image_text.c) | <img src="textures/textures_image_text.png" alt="textures_image_text" width="80"> | ⭐️⭐️☆☆ | 1.8 | 4.0 | [Ray](https://github.com/raysan5) |
| 63 | [textures_to_image](textures/textures_to_image.c) | <img src="textures/textures_to_image.png" alt="textures_to_image" width="80"> | ⭐️☆☆☆ | 1.3 | 4.0 | [Ray](https://github.com/raysan5) |
| 64 | [textures_raw_data](textures/textures_raw_data.c) | <img src="textures/textures_raw_data.png" alt="textures_raw_data" width="80"> | ⭐️⭐️⭐️☆ | 1.3 | 3.5 | [Ray](https://github.com/raysan5) |
| 65 | [textures_particles_blending](textures/textures_particles_blending.c) | <img src="textures/textures_particles_blending.png" alt="textures_particles_blending" width="80"> | ⭐️☆☆☆ | 1.7 | 3.5 | [Ray](https://github.com/raysan5) |
| 66 | [textures_npatch_drawing](textures/textures_npatch_drawing.c) | <img src="textures/textures_npatch_drawing.png" alt="textures_npatch_drawing" width="80"> | ⭐️⭐️⭐️☆ | 2.0 | 2.5 | [Jorge A. Gomes](https://github.com/overdev) |
| 67 | [textures_background_scrolling](textures/textures_background_scrolling.c) | <img src="textures/textures_background_scrolling.png" alt="textures_background_scrolling" width="80"> | ⭐️☆☆☆ | 2.0 | 2.5 | [Ray](https://github.com/raysan5) |
| 68 | [textures_sprite_anim](textures/textures_sprite_anim.c) | <img src="textures/textures_sprite_anim.png" alt="textures_sprite_anim" width="80"> | ⭐️⭐️☆☆ | 1.3 | 1.3 | [Ray](https://github.com/raysan5) |
| 69 | [textures_sprite_button](textures/textures_sprite_button.c) | <img src="textures/textures_sprite_button.png" alt="textures_sprite_button" width="80"> | ⭐️⭐️☆☆ | 2.5 | 2.5 | [Ray](https://github.com/raysan5) |
| 70 | [textures_sprite_explosion](textures/textures_sprite_explosion.c) | <img src="textures/textures_sprite_explosion.png" alt="textures_sprite_explosion" width="80"> | ⭐️⭐️☆☆ | 2.5 | 3.5 | [Ray](https://github.com/raysan5) |
| 71 | [textures_bunnymark](textures/textures_bunnymark.c) | <img src="textures/textures_bunnymark.png" alt="textures_bunnymark" width="80"> | ⭐️⭐️⭐️☆ | 1.6 | 2.5 | [Ray](https://github.com/raysan5) |
| 72 | [textures_mouse_painting](textures/textures_mouse_painting.c) | <img src="textures/textures_mouse_painting.png" alt="textures_mouse_painting" width="80"> | ⭐️⭐️⭐️☆ | 3.0 | 3.0 | [Chris Dill](https://github.com/MysteriousSpace) |
| 73 | [textures_blend_modes](textures/textures_blend_modes.c) | <img src="textures/textures_blend_modes.png" alt="textures_blend_modes" width="80"> | ⭐️☆☆☆ | 3.5 | 3.5 | [Karlo Licudine](https://github.com/accidentalrebel) |
| 74 | [textures_draw_tiled](textures/textures_draw_tiled.c) | <img src="textures/textures_draw_tiled.png" alt="textures_draw_tiled" width="80"> | ⭐️⭐️⭐️☆ | 3.0 | 4.2 | [Vlad Adrian](https://github.com/demizdor) |
| 75 | [textures_polygon](textures/textures_polygon.c) | <img src="textures/textures_polygon.png" alt="textures_polygon" width="80"> | ⭐️☆☆☆ | 3.7 | 3.7 | [Chris Camacho](https://github.com/chriscamacho) |
| 76 | [textures_fog_of_war](textures/textures_fog_of_war.c) | <img src="textures/textures_fog_of_war.png" alt="textures_fog_of_war" width="80"> | ⭐️⭐️⭐️☆ | 4.2 | 4.2 | [Ray](https://github.com/raysan5) |
| 77 | [textures_gif_player](textures/textures_gif_player.c) | <img src="textures/textures_gif_player.png" alt="textures_gif_player" width="80"> | ⭐️⭐️⭐️☆ | 4.2 | 4.2 | [Ray](https://github.com/raysan5) |
| 78 | [textures_image_kernel](textures/textures_image_kernel.c) | <img src="textures/textures_image_kernel.png" alt="textures_image_kernel" width="80"> | ⭐️⭐️⭐️⭐️ | 1.3 | 1.3 | [Karim Salem](https://github.com/kimo-s) |
| 79 | [textures_image_channel](textures/textures_image_channel.c) | <img src="textures/textures_image_channel.png" alt="textures_image_channel" width="80"> | ⭐️⭐️☆☆ | 5.1-dev | 5.1-dev | [Bruno Cabral](https://github.com/brccabral) |
| 80 | [textures_image_rotate](textures/textures_image_rotate.c) | <img src="textures/textures_image_rotate.png" alt="textures_image_rotate" width="80"> | ⭐️⭐️☆☆ | 1.0 | 1.0 | [Ray](https://github.com/raysan5) |
| 81 | [textures_textured_curve](textures/textures_textured_curve.c) | <img src="textures/textures_textured_curve.png" alt="textures_textured_curve" width="80"> | ⭐️⭐️⭐️☆ | 4.5 | 4.5 | [Jeffery Myers](https://github.com/JeffM2501) |

### category: text

Examples using raylib text functionality, including sprite fonts loading/generation and text drawing, provided by raylib [text](../src/text.c) module.

| ## | example  | image  | difficulty<br>level | version<br>created | last version<br>updated | original<br>developer |
|----|----------|--------|:-------------------:|:------------------:|:-----------------------:|:----------------------|
| 82 | [text_raylib_fonts](text/text_raylib_fonts.c) | <img src="text/text_raylib_fonts.png" alt="text_raylib_fonts" width="80"> | ⭐️☆☆☆ | 1.7 | 3.7 | [Ray](https://github.com/raysan5) |
| 83 | [text_font_spritefont](text/text_font_spritefont.c) | <img src="text/text_font_spritefont.png" alt="text_font_spritefont" width="80"> | ⭐️☆☆☆ | 1.0 | 1.0 | [Ray](https://github.com/raysan5) |
| 84 | [text_font_filters](text/text_font_filters.c) | <img src="text/text_font_filters.png" alt="text_font_filters" width="80"> | ⭐️⭐️☆☆ | 1.3 | 4.2 | [Ray](https://github.com/raysan5) |
| 85 | [text_font_loading](text/text_font_loading.c) | <img src="text/text_font_loading.png" alt="text_font_loading" width="80"> | ⭐️☆☆☆ | 1.4 | 3.0 | [Ray](https://github.com/raysan5) |
| 86 | [text_font_sdf](text/text_font_sdf.c) | <img src="text/text_font_sdf.png" alt="text_font_sdf" width="80"> | ⭐️⭐️⭐️☆ | 1.3 | 4.0 | [Ray](https://github.com/raysan5) |
| 87 | [text_format_text](text/text_format_text.c) | <img src="text/text_format_text.png" alt="text_format_text" width="80"> | ⭐️☆☆☆ | 1.1 | 3.0 | [Ray](https://github.com/raysan5) |
| 88 | [text_input_box](text/text_input_box.c) | <img src="text/text_input_box.png" alt="text_input_box" width="80"> | ⭐️⭐️☆☆ | 1.7 | 3.5 | [Ray](https://github.com/raysan5) |
| 89 | [text_writing_anim](text/text_writing_anim.c) | <img src="text/text_writing_anim.png" alt="text_writing_anim" width="80"> | ⭐️⭐️☆☆ | 1.4 | 1.4 | [Ray](https://github.com/raysan5) |
| 90 | [text_rectangle_bounds](text/text_rectangle_bounds.c) | <img src="text/text_rectangle_bounds.png" alt="text_rectangle_bounds" width="80"> | ⭐️⭐️⭐️⭐️ | 2.5 | 4.0 | [Vlad Adrian](https://github.com/demizdor) |
| 91 | [text_unicode](text/text_unicode.c) | <img src="text/text_unicode.png" alt="text_unicode" width="80"> | ⭐️⭐️⭐️⭐️ | 2.5 | 4.0 | [Vlad Adrian](https://github.com/demizdor) |
| 92 | [text_draw_3d](text/text_draw_3d.c) | <img src="text/text_draw_3d.png" alt="text_draw_3d" width="80"> | ⭐️⭐️⭐️⭐️ | 3.5 | 4.0 | [Vlad Adrian](https://github.com/demizdor) |
| 93 | [text_codepoints_loading](text/text_codepoints_loading.c) | <img src="text/text_codepoints_loading.png" alt="text_codepoints_loading" width="80"> | ⭐️⭐️⭐️☆ | 4.2 | 4.2 | [Ray](https://github.com/raysan5) |

### category: models

Examples using raylib models functionality, including models loading/generation and drawing, provided by raylib [models](../src/models.c) module.

| ## | example  | image  | difficulty<br>level | version<br>created | last version<br>updated | original<br>developer |
|----|----------|--------|:-------------------:|:------------------:|:-----------------------:|:----------------------|
| 94 | [models_animation](models/models_animation.c) | <img src="models/models_animation.png" alt="models_animation" width="80"> | ⭐️⭐️☆☆ | 2.5 | 3.5 | [Culacant](https://github.com/culacant) |
| 95 | [models_billboard](models/models_billboard.c) | <img src="models/models_billboard.png" alt="models_billboard" width="80"> | ⭐️⭐️⭐️☆ | 1.3 | 3.5 | [Ray](https://github.com/raysan5) |
| 96 | [models_box_collisions](models/models_box_collisions.c) | <img src="models/models_box_collisions.png" alt="models_box_collisions" width="80"> | ⭐️☆☆☆ | 1.3 | 3.5 | [Ray](https://github.com/raysan5) |
| 97 | [models_cubicmap](models/models_cubicmap.c) | <img src="models/models_cubicmap.png" alt="models_cubicmap" width="80"> | ⭐️⭐️☆☆ | 1.8 | 3.5 | [Ray](https://github.com/raysan5) |
| 98 | [models_first_person_maze](models/models_first_person_maze.c) | <img src="models/models_first_person_maze.png" alt="models_first_person_maze" width="80"> | ⭐️⭐️☆☆ | 2.5 | 3.5 | [Ray](https://github.com/raysan5) |
| 99 | [models_geometric_shapes](models/models_geometric_shapes.c) | <img src="models/models_geometric_shapes.png" alt="models_geometric_shapes" width="80"> | ⭐️☆☆☆ | 1.0 | 3.5 | [Ray](https://github.com/raysan5) |
| 100 | [models_mesh_generation](models/models_mesh_generation.c) | <img src="models/models_mesh_generation.png" alt="models_mesh_generation" width="80"> | ⭐️⭐️☆☆ | 1.8 | 4.0 | [Ray](https://github.com/raysan5) |
| 101 | [models_mesh_picking](models/models_mesh_picking.c) | <img src="models/models_mesh_picking.png" alt="models_mesh_picking" width="80"> | ⭐️⭐️⭐️☆ | 1.7 | 4.0 | [Joel Davis](https://github.com/joeld42) |
| 102 | [models_loading](models/models_loading.c) | <img src="models/models_loading.png" alt="models_loading" width="80"> | ⭐️☆☆☆ | 2.0 | 4.2 | [Ray](https://github.com/raysan5) |
| 103 | [models_loading_gltf](models/models_loading_gltf.c) | <img src="models/models_loading_gltf.png" alt="models_loading_gltf" width="80"> | ⭐️☆☆☆ | 3.7 | 4.2 | [Ray](https://github.com/raysan5) |
| 104 | [models_loading_vox](models/models_loading_vox.c) | <img src="models/models_loading_vox.png" alt="models_loading_vox" width="80"> | ⭐️☆☆☆ | 4.0 | 4.0 | [Johann Nadalutti](https://github.com/procfxgen) |
| 105 | [models_loading_m3d](models/models_loading_m3d.c) | <img src="models/models_loading_m3d.png" alt="models_loading_m3d" width="80"> | ⭐️⭐️☆☆ | 4.5 | 4.5 | [bzt](https://bztsrc.gitlab.io/model3d) |
| 106 | [models_orthographic_projection](models/models_orthographic_projection.c) | <img src="models/models_orthographic_projection.png" alt="models_orthographic_projection" width="80"> | ⭐️☆☆☆ | 2.0 | 3.7 | [Max Danielsson](https://github.com/autious) |
| 107 | [models_point_rendering](models/models_point_rendering.c) | <img src="models/models_point_rendering.png" alt="models_point_rendering" width="80"> | ⭐️⭐️⭐️☆ | 5.0 | 5.0 | [Reese Gallagher](https://github.com/satchelfrost) |
| 108 | [models_rlgl_solar_system](models/models_rlgl_solar_system.c) | <img src="models/models_rlgl_solar_system.png" alt="models_rlgl_solar_system" width="80"> | ⭐️⭐️⭐️⭐️ | 2.5 | 4.0 | [Ray](https://github.com/raysan5) |
| 109 | [models_yaw_pitch_roll](models/models_yaw_pitch_roll.c) | <img src="models/models_yaw_pitch_roll.png" alt="models_yaw_pitch_roll" width="80"> | ⭐️⭐️☆☆ | 1.8 | 4.0 | [Berni](https://github.com/Berni8k) |
| 110 | [models_waving_cubes](models/models_waving_cubes.c) | <img src="models/models_waving_cubes.png" alt="models_waving_cubes" width="80"> | ⭐️⭐️⭐️☆ | 2.5 | 3.7 | [Codecat](https://github.com/codecat) |
| 111 | [models_heightmap](models/models_heightmap.c) | <img src="models/models_heightmap.png" alt="models_heightmap" width="80"> | ⭐️☆☆☆ | 1.8 | 3.5 | [Ray](https://github.com/raysan5) |
| 112 | [models_skybox](models/models_skybox.c) | <img src="models/models_skybox.png" alt="models_skybox" width="80"> | ⭐️⭐️☆☆ | 1.8 | 4.0 | [Ray](https://github.com/raysan5) |
| 113 | [models_draw_cube_texture](models/models_draw_cube_texture.c) | <img src="models/models_draw_cube_texture.png" alt="models_draw_cube_texture" width="80"> | ⭐️⭐️☆☆ | 4.5 | 4.5 | [Ray](https://github.com/raysan5) |
| 114 | [models_gpu_skinning](models/models_gpu_skinning.c) | <img src="models/models_gpu_skinning.png" alt="models_gpu_skinning" width="80"> | ⭐️⭐️⭐️☆ | 4.5 | 4.5 | [Daniel Holden](https://github.com/orangeduck) |
| 115 | [models_bone_socket](models/models_bone_socket.c) | <img src="models/models_bone_socket.png" alt="models_bone_socket" width="80"> | ⭐️⭐️⭐️⭐️ | 4.5 | 4.5 | [iP](https://github.com/ipzaur) |
| 116 | [models_tesseract_view](models/models_tesseract_view.c) | <img src="models/models_tesseract_view.png" alt="models_tesseract_view" width="80"> | ⭐️⭐️☆☆ | 5.6-dev | 5.6-dev | [Timothy van der Valk](https://github.com/arceryz) |

### category: shaders

Examples using raylib shaders functionality, including shaders loading, parameters configuration and drawing using them (model shaders and postprocessing shaders). This functionality is directly provided by raylib [rlgl](../src/rlgl.c) module.

| ## | example  | image  | difficulty<br>level | version<br>created | last version<br>updated | original<br>developer |
|----|----------|--------|:-------------------:|:------------------:|:-----------------------:|:----------------------|
| 117 | [shaders_basic_lighting](shaders/shaders_basic_lighting.c) | <img src="shaders/shaders_basic_lighting.png" alt="shaders_basic_lighting" width="80"> | ⭐️⭐️⭐️⭐️ | 3.0 | 4.2 | [Chris Camacho](https://github.com/chriscamacho) |
| 118 | [shaders_model_shader](shaders/shaders_model_shader.c) | <img src="shaders/shaders_model_shader.png" alt="shaders_model_shader" width="80"> | ⭐️⭐️☆☆ | 1.3 | 3.7 | [Ray](https://github.com/raysan5) |
| 119 | [shaders_shapes_textures](shaders/shaders_shapes_textures.c) | <img src="shaders/shaders_shapes_textures.png" alt="shaders_shapes_textures" width="80"> | ⭐️⭐️☆☆ | 1.7 | 3.7 | [Ray](https://github.com/raysan5) |
| 120 | [shaders_custom_uniform](shaders/shaders_custom_uniform.c) | <img src="shaders/shaders_custom_uniform.png" alt="shaders_custom_uniform" width="80"> | ⭐️⭐️☆☆ | 1.3 | 4.0 | [Ray](https://github.com/raysan5) |
| 121 | [shaders_postprocessing](shaders/shaders_postprocessing.c) | <img src="shaders/shaders_postprocessing.png" alt="shaders_postprocessing" width="80"> | ⭐️⭐️⭐️☆ | 1.3 | 4.0 | [Ray](https://github.com/raysan5) |
| 122 | [shaders_palette_switch](shaders/shaders_palette_switch.c) | <img src="shaders/shaders_palette_switch.png" alt="shaders_palette_switch" width="80"> | ⭐️⭐️⭐️☆ | 2.5 | 3.7 | [Marco Lizza](https://github.com/MarcoLizza) |
| 123 | [shaders_raymarching](shaders/shaders_raymarching.c) | <img src="shaders/shaders_raymarching.png" alt="shaders_raymarching" width="80"> | ⭐️⭐️⭐️⭐️ | 2.0 | 4.2 | [Ray](https://github.com/raysan5) |
| 124 | [shaders_texture_drawing](shaders/shaders_texture_drawing.c) | <img src="shaders/shaders_texture_drawing.png" alt="shaders_texture_drawing" width="80"> | ⭐️⭐️☆☆ | 2.0 | 3.7 | [Michał Ciesielski](https://github.com/ciessielski) |
| 125 | [shaders_texture_outline](shaders/shaders_texture_outline.c) | <img src="shaders/shaders_texture_outline.png" alt="shaders_texture_outline" width="80"> | ⭐️⭐️⭐️☆ | 4.0 | 4.0 | [Samuel Skiff](https://github.com/GoldenThumbs) |
| 126 | [shaders_texture_waves](shaders/shaders_texture_waves.c) | <img src="shaders/shaders_texture_waves.png" alt="shaders_texture_waves" width="80"> | ⭐️⭐️☆☆ | 2.5 | 3.7 | [Anata](https://github.com/anatagawa) |
| 127 | [shaders_julia_set](shaders/shaders_julia_set.c) | <img src="shaders/shaders_julia_set.png" alt="shaders_julia_set" width="80"> | ⭐️⭐️⭐️☆ | 2.5 | 4.0 | [Josh Colclough](https://github.com/joshcol9232) |
| 128 | [shaders_eratosthenes](shaders/shaders_eratosthenes.c) | <img src="shaders/shaders_eratosthenes.png" alt="shaders_eratosthenes" width="80"> | ⭐️⭐️⭐️☆ | 2.5 | 4.0 | [ProfJski](https://github.com/ProfJski) |
| 129 | [shaders_fog](shaders/shaders_fog.c) | <img src="shaders/shaders_fog.png" alt="shaders_fog" width="80"> | ⭐️⭐️⭐️☆ | 2.5 | 3.7 | [Chris Camacho](https://github.com/chriscamacho) |
| 130 | [shaders_simple_mask](shaders/shaders_simple_mask.c) | <img src="shaders/shaders_simple_mask.png" alt="shaders_simple_mask" width="80"> | ⭐️⭐️☆☆ | 2.5 | 3.7 | [Chris Camacho](https://github.com/chriscamacho) |
| 131 | [shaders_hot_reloading](shaders/shaders_hot_reloading.c) | <img src="shaders/shaders_hot_reloading.png" alt="shaders_hot_reloading" width="80"> | ⭐️⭐️⭐️☆ | 3.0 | 3.5 | [Ray](https://github.com/raysan5) |
| 132 | [shaders_mesh_instancing](shaders/shaders_mesh_instancing.c) | <img src="shaders/shaders_mesh_instancing.png" alt="shaders_mesh_instancing" width="80"> | ⭐️⭐️⭐️⭐️ | 3.7 | 4.2 | [seanpringle](https://github.com/seanpringle) |
| 133 | [shaders_multi_sample2d](shaders/shaders_multi_sample2d.c) | <img src="shaders/shaders_multi_sample2d.png" alt="shaders_multi_sample2d" width="80"> | ⭐️⭐️☆☆ | 3.5 | 3.5 | [Ray](https://github.com/raysan5) |
| 134 | [shaders_spotlight](shaders/shaders_spotlight.c) | <img src="shaders/shaders_spotlight.png" alt="shaders_spotlight" width="80"> | ⭐️⭐️☆☆ | 2.5 | 3.7 | [Chris Camacho](https://github.com/chriscamacho) |
| 135 | [shaders_deferred_render](shaders/shaders_deferred_render.c) | <img src="shaders/shaders_deferred_render.png" alt="shaders_deferred_render" width="80"> | ⭐️⭐️⭐️⭐️ | 4.5 | 4.5 | [Justin Andreas Lacoste](https://github.com/27justin) |
| 136 | [shaders_hybrid_render](shaders/shaders_hybrid_render.c) | <img src="shaders/shaders_hybrid_render.png" alt="shaders_hybrid_render" width="80"> | ⭐️⭐️⭐️⭐️ | 4.2 | 4.2 | [Buğra Alptekin Sarı](https://github.com/BugraAlptekinSari) |
| 137 | [shaders_texture_tiling](shaders/shaders_texture_tiling.c) | <img src="shaders/shaders_texture_tiling.png" alt="shaders_texture_tiling" width="80"> | ⭐️⭐️☆☆ | 4.5 | 4.5 | [Luis Almeida](https://github.com/luis605) |
| 138 | [shaders_shadowmap](shaders/shaders_shadowmap.c) | <img src="shaders/shaders_shadowmap.png" alt="shaders_shadowmap" width="80"> | ⭐️⭐️⭐️⭐️ | 5.0 | 5.0 | [TheManTheMythTheGameDev](https://github.com/TheManTheMythTheGameDev) |
| 139 | [shaders_vertex_displacement](shaders/shaders_vertex_displacement.c) | <img src="shaders/shaders_vertex_displacement.png" alt="shaders_vertex_displacement" width="80"> | ⭐️⭐️⭐️☆ | 5.0 | 4.5 | [Alex ZH](https://github.com/ZzzhHe) |
| 140 | [shaders_write_depth](shaders/shaders_write_depth.c) | <img src="shaders/shaders_write_depth.png" alt="shaders_write_depth" width="80"> | ⭐️⭐️☆☆ | 4.2 | 4.2 | [Buğra Alptekin Sarı](https://github.com/BugraAlptekinSari) |
| 141 | [shaders_basic_pbr](shaders/shaders_basic_pbr.c) | <img src="shaders/shaders_basic_pbr.png" alt="shaders_basic_pbr" width="80"> | ⭐️⭐️⭐️⭐️ | 5.0 | 5.1-dev | [Afan OLOVCIC](https://github.com/_DevDad) |
| 142 | [shaders_lightmap](shaders/shaders_lightmap.c) | <img src="shaders/shaders_lightmap.png" alt="shaders_lightmap" width="80"> | ⭐️⭐️⭐️☆ | 4.5 | 4.5 | [Jussi Viitala](https://github.com/nullstare) |
| 143 | [shaders_rounded_rectangle](shaders/shaders_rounded_rectangle.c) | <img src="shaders/shaders_rounded_rectangle.png" alt="shaders_rounded_rectangle" width=80> | ⭐️⭐️⭐️☆ | 5.5 | 5.5 | [Anstro Pleuton](https://github.com/anstropleuton) |
| 144 | [shaders_view_depth](shaders/shaders_view_depth.c) | <img src="shaders/shaders_view_depth.png" alt="shaders_view_depth" width="80"> | ⭐️⭐️⭐️☆ | 5.6-dev | 5.6-dev | [Luís Almeida](https://github.com/luis605) |

### category: audio

Examples using raylib audio functionality, including sound/music loading and playing. This functionality is provided by raylib [raudio](../src/raudio.c) module. Note this module can be used standalone independently of raylib, check [raudio_standalone](others/raudio_standalone.c) example.

| ## | example  | image  | difficulty<br>level | version<br>created | last version<br>updated | original<br>developer |
|----|----------|--------|:-------------------:|:------------------:|:-----------------------:|:----------------------|
| 145 | [audio_module_playing](audio/audio_module_playing.c) | <img src="audio/audio_module_playing.png" alt="audio_module_playing" width="80"> | ⭐️☆☆☆ | 1.5 | 3.5 | [Ray](https://github.com/raysan5) |
| 146 | [audio_music_stream](audio/audio_music_stream.c) | <img src="audio/audio_music_stream.png" alt="audio_music_stream" width="80"> | ⭐️☆☆☆ | 1.3 | 4.2 | [Ray](https://github.com/raysan5) |
| 147 | [audio_raw_stream](audio/audio_raw_stream.c) | <img src="audio/audio_raw_stream.png" alt="audio_raw_stream" width="80"> | ⭐️⭐️⭐️☆ | 1.6 | 4.2 | [Ray](https://github.com/raysan5) |
| 148 | [audio_sound_loading](audio/audio_sound_loading.c) | <img src="audio/audio_sound_loading.png" alt="audio_sound_loading" width="80"> | ⭐️☆☆☆ | 1.1 | 3.5 | [Ray](https://github.com/raysan5) |
| 149 | [audio_mixed_processor](audio/audio_mixed_processor.c) | <img src="audio/audio_mixed_processor.png" alt="audio_mixed_processor" width="80"> | ⭐️⭐️⭐️⭐️ | 4.2 | 4.2 | [hkc](https://github.com/hatkidchan) |
| 150 | [audio_stream_effects](audio/audio_stream_effects.c) | <img src="audio/audio_stream_effects.png" alt="audio_stream_effects" width="80"> | ⭐️⭐️⭐️⭐️ | 4.2 | 5.0 | [Ray](https://github.com/raysan5) |
| 151 | [audio_sound_multi](audio/audio_sound_multi.c) | <img src="audio/audio_sound_multi.png" alt="audio_sound_multi" width="80"> | ⭐️⭐️☆☆ | 4.6 | 4.6 | [Jeffery Myers](https://github.com/JeffM2501) |
| 152 | [audio_sound_positioning](audio/audio_sound_positioning.c) | <img src="audio/audio_sound_positioning.png" alt="audio_sound_positioning" width="80"> | ⭐️⭐️☆☆ | 5.5 | 5.5 | [Le Juez Victor](https://github.com/Bigfoot71) |

### category: others

Examples showing raylib misc functionality that does not fit in other categories, like standalone modules usage or examples integrating external libraries.

| ## | example  | image  | difficulty<br>level | version<br>created | last version<br>updated | original<br>developer |
|----|----------|--------|:-------------------:|:------------------:|:-----------------------:|:----------------------|
| 153 | [rlgl_standalone](others/rlgl_standalone.c) | <img src="others/rlgl_standalone.png" alt="rlgl_standalone" width="80"> | ⭐️⭐️⭐️⭐️ | 1.6 | 4.0 | [Ray](https://github.com/raysan5) |
| 154 | [rlgl_compute_shader](others/rlgl_compute_shader.c) | <img src="others/rlgl_compute_shader.png" alt="rlgl_compute_shader" width="80"> | ⭐️⭐️⭐️⭐️ | 4.0 | 4.0 | [Teddy Astie](https://github.com/tsnake41) |
| 155 | [easings_testbed](others/easings_testbed.c) | <img src="others/easings_testbed.png" alt="easings_testbed" width="80"> | ⭐️⭐️⭐️☆ | 2.5 | 3.0 | [Juan Miguel López](https://github.com/flashback-fx) |
| 156 | [raylib_opengl_interop](others/raylib_opengl_interop.c) | <img src="others/raylib_opengl_interop.png" alt="raylib_opengl_interop" width="80"> | ⭐️⭐️⭐️⭐️ | 3.8 | 4.0 | [Stephan Soller](https://github.com/arkanis) |
| 157 | [embedded_files_loading](others/embedded_files_loading.c) | <img src="others/embedded_files_loading.png" alt="embedded_files_loading" width="80"> | ⭐️⭐️☆☆ | 3.0 | 3.5 | [Kristian Holmgren](https://github.com/defutura) |
| 158 | [raymath_vector_angle](others/raymath_vector_angle.c) | <img src="others/raymath_vector_angle.png" alt="raymath_vector_angle" width="80"> | ⭐️⭐️☆☆ | 1.0 | 4.6 | [Ray](https://github.com/raysan5) |

As always contributions are welcome, feel free to send new examples! Here is an [examples template](examples_template.c) to start with!
