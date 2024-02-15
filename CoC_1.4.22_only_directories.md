# Table of contents - Call of Chernobyl 1.4.22

## config

- [ai.db](#ai)
- [anims.db](#anims)
- [configs.db](#configs)
- [scripts.db](#scripts)
- [shaders.db](#shaders)
- [spawns.db](#spawns)
- [xr.db](#xr)

## maps

- [fake_start.db](#fake_start)
- [jupiter.db](#jupiter)
- [jupiter_underground.db](#jupiter_underground)
- [k00_marsh.db](#k00_marsh)
- [k01_darkscape.db](#k01_darkscape)
- [k02_trucks_cemetery.db](#k02_trucks_cemetery)
- [l01_escape.db](#l01_escape)
- [l02_garbage.db](#l02_garbage)
- [l03_agroprom.db](#l03_agroprom)
- [l03u_agr_underground.db](#l03u_agr_underground)
- [l04_darkvalley.db](#l04_darkvalley)
- [l04u_labx18.db](#l04u_labx18)
- [l05_bar.db](#l05_bar)
- [l06_rostok.db](#l06_rostok)
- [l07_military.db](#l07_military)
- [l08_yantar.db](#l08_yantar)
- [l08u_brainlab.db](#l08u_brainlab)
- [l09_deadcity.db](#l09_deadcity)
- [l10_limansk.db](#l10_limansk)
- [l10_radar.db](#l10_radar)
- [l10_red_forest.db](#l10_red_forest)
- [l10u_bunker.db](#l10u_bunker)
- [l11_hospital.db](#l11_hospital)
- [l11_pripyat.db](#l11_pripyat)
- [l12_stancia.db](#l12_stancia)
- [l12_stancia_2.db](#l12_stancia_2)
- [l12u_control_monolith.db](#l12u_control_monolith)
- [l12u_sarcofag.db](#l12u_sarcofag)
- [l13_generators.db](#l13_generators)
- [l13u_warlab.db](#l13u_warlab)
- [labx8.db](#labx8)
- [pripyat.db](#pripyat)
- [zaton.db](#zaton)

## patch

- [xpatch_meshes.db](#xpatch_meshes)
- [xpatch_sounds.db](#xpatch_sounds)
- [xpatch_textures.db](#xpatch_textures)

## resource

- [meshes.db0](#meshes0)
- [meshes.db1](#meshes1)
- [textures.db0](#textures0)
- [textures.db1](#textures1)
- [textures.db2](#textures2)
- [textures.db3](#textures3)

## sound

- [sounds.db](#sounds)

## config - directory

<a id="ai"></a>

### ai.db

```console
`-- ai
    |-- alife
    `-- common
```

<a id="anims"></a>

### anims.db

```console
`-- anims
    |-- benchmarks
    |-- camera_effects
    |   |-- actor_move
    |   |-- scenario_cam
    |   |   |-- agraprom_underground
    |   |   |-- jupiter
    |   |   |-- marsh
    |   |   |-- pripyat
    |   |   `-- zaton
    |   `-- weapon
    |-- helicopter
    `-- path
```

<a id="configs"></a>

### configs.db

```console
`-- configs
    |-- ai_tweaks
    |-- creatures
    |-- debug
    |-- environment
    |   |-- ambient_channels
    |   |-- ambients
    |   |-- fog
    |   |-- weather_effects
    |   `-- weathers
    |-- gameplay
    |-- misc
    |   |-- outfit_upgrades
    |   |-- sound
    |   |-- trade
    |   `-- upgrade_infos
    |-- models
    |   |-- capture
    |   |-- objects
    |   |-- vehicles
    |   `-- weapons
    |-- mp
    |   |-- soundmessages
    |   `-- weapons_mp
    |-- plugins
    |-- prefetch
    |-- scripts
    |   |-- agroprom
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- agroprom_underground
    |   |   `-- smart
    |   |-- bar
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- bun
    |   |   `-- anomaly
    |   |-- bunker
    |   |   `-- smart
    |   |-- darkscape
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- darkvalley
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- dead_city
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- escape
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- evac
    |   |   `-- smart
    |   |-- garbage
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- generators
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- jupiter
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- katacomb_hospital
    |   |   `-- smart
    |   |-- labx16
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- labx18
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- labx8
    |   |-- limansk
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- marsh
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- military
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- monolith_control
    |   |   `-- smart
    |   |-- pripyat
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- radar
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- red_forest
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- rostok
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- sarcofag
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- stancia_1
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- stancia_2
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- trucks_cemetery
    |   |   |-- anomaly
    |   |   `-- smart
    |   |-- underpass
    |   |   `-- smart
    |   |-- warlab
    |   |-- yantar
    |   |   |-- anomaly
    |   |   `-- smart
    |   `-- zaton
    |       |-- anomaly
    |       `-- smart
    |-- text
    |   |-- eng
    |   `-- rus
    |-- ui
    |   `-- textures_descr
    |-- weapons
    |   `-- upgrades
    |-- weathers
    `-- zones
```

<a id="scripts"></a>

### scripts.db

```console
`-- scripts
```

<a id="shaders"></a>

### shaders.db

```console
`-- shaders
    |-- r1
    |   |-- objects
    |   |   `-- r1
    |   |       |-- add_point.ps
    |   |       |-- add_ppa.ps
    |   |       |-- add_spot.ps
    |   |       |-- avg2.ps
    |   |       |-- avg4.ps
    |   |       |-- base_lplanes.ps
    |   |       |-- base_lplanes.vs
    |   |       |-- clouds.ps
    |   |       |-- clouds.vs
    |   |       |-- detail.ps
    |   |       |-- detail_still.vs
    |   |       |-- detail_wave.vs
    |   |       |-- editor.vs
    |   |       |-- font2.ps
    |   |       |-- hud3d.ps
    |   |       |-- hud3d.vs
    |   |       |-- hud_font.ps
    |   |       |-- impl.ps
    |   |       |-- impl.vs
    |   |       |-- impl_dt.ps
    |   |       |-- impl_dt.vs
    |   |       |-- impl_l.ps
    |   |       |-- impl_l.vs
    |   |       |-- impl_point.vs
    |   |       |-- impl_spot.vs
    |   |       |-- lmap.ps
    |   |       |-- lmap.vs
    |   |       |-- lmap_dt.ps
    |   |       |-- lmap_dt.vs
    |   |       |-- lmap_l.ps
    |   |       |-- lmap_l.vs
    |   |       |-- lmap_point.vs
    |   |       |-- lmap_spot.vs
    |   |       |-- lmape.ps
    |   |       |-- lmape.vs
    |   |       |-- lod.ps
    |   |       |-- lod.vs
    |   |       |-- model_def_hq.ps
    |   |       |-- model_def_hq.vs
    |   |       |-- model_def_lplanes.vs
    |   |       |-- model_def_lq.ps
    |   |       |-- model_def_lq.vs
    |   |       |-- model_def_lqs.vs
    |   |       |-- model_def_point.vs
    |   |       |-- model_def_shadow.vs
    |   |       |-- model_def_spot.vs
    |   |       |-- model_distort.vs
    |   |       |-- model_distort2t.vs
    |   |       |-- model_distort4ghost.vs
    |   |       |-- model_distort4glass.vs
    |   |       |-- model_distort_inv.vs
    |   |       |-- model_env.ps
    |   |       |-- model_env_hq.ps
    |   |       |-- model_env_hq.vs
    |   |       |-- model_env_lq.ps
    |   |       |-- model_env_lq.vs
    |   |       |-- model_env_sl.ps
    |   |       |-- model_shadow.ps
    |   |       |-- particle.ps
    |   |       |-- particle.vs
    |   |       |-- particle2t.ps
    |   |       |-- particle_alphaonly.ps
    |   |       |-- particle_distort.ps
    |   |       |-- portal.vs
    |   |       |-- postprocess.ps
    |   |       |-- postprocess_cm_pre.ps
    |   |       |-- postprocess_d.ps
    |   |       |-- simple.ps
    |   |       |-- simple.vs
    |   |       |-- simple_color.ps
    |   |       |-- simple_color.vs
    |   |       |-- simple_point.vs
    |   |       |-- simple_spot.vs
    |   |       |-- sky2.ps
    |   |       |-- sky2.vs
    |   |       |-- sun2.ps
    |   |       |-- tree_s.vs
    |   |       |-- tree_s_dt.vs
    |   |       |-- tree_s_point.vs
    |   |       |-- tree_s_spot.vs
    |   |       |-- tree_test.vs
    |   |       |-- tree_w.vs
    |   |       |-- tree_w_dt.vs
    |   |       |-- tree_w_point.vs
    |   |       |-- tree_w_spot.vs
    |   |       |-- tree_wave.vs
    |   |       |-- tree_wave_dt.vs
    |   |       |-- tree_wave_point.vs
    |   |       |-- tree_wave_spot.vs
    |   |       |-- vert.ps
    |   |       |-- vert.vs
    |   |       |-- vert_dt.ps
    |   |       |-- vert_dt.vs
    |   |       |-- vert_l.ps
    |   |       |-- vert_l.vs
    |   |       |-- vert_point.vs
    |   |       |-- vert_spot.vs
    |   |       |-- water.ps
    |   |       |-- water.vs
    |   |       |-- waterd.ps
    |   |       |-- waterd.vs
    |   |       |-- wmark.vs
    |   |       |-- wmark_point.vs
    |   |       |-- wmark_spot.vs
    |   |       |-- wmarkmult.ps
    |   |       `-- yuv2rgb.ps
    |   |-- old
    |   |-- shared
    |   `-- test
    |-- r2
    |   |-- shared
    |   `-- test
    |-- r3
    |   |-- dx11
    |   |-- objects
    |   |   |-- r3
    |   |   |   |-- accum_base.ps
    |   |   |   |-- accum_emissive.ps
    |   |   |   |-- accum_emissivel.ps
    |   |   |   |-- accum_indirect.ps
    |   |   |   |-- accum_indirect_msaa.ps
    |   |   |   |-- accum_indirect_nomsaa.ps
    |   |   |   |-- accum_mask.vs
    |   |   |   |-- accum_omni_normal.ps
    |   |   |   |-- accum_omni_normal_msaa.ps
    |   |   |   |-- accum_omni_normal_nomsaa.ps
    |   |   |   |-- accum_omni_transluent.ps
    |   |   |   |-- accum_omni_transluent_msaa.ps
    |   |   |   |-- accum_omni_transluent_nomsaa.ps
    |   |   |   |-- accum_omni_unshadowed.ps
    |   |   |   |-- accum_omni_unshadowed_msaa.ps
    |   |   |   |-- accum_omni_unshadowed_nomsaa.ps
    |   |   |   |-- accum_spot_fullsize.ps
    |   |   |   |-- accum_spot_fullsize_msaa.ps
    |   |   |   |-- accum_spot_fullsize_nomsaa.ps
    |   |   |   |-- accum_spot_normal.ps
    |   |   |   |-- accum_spot_normal_msaa.ps
    |   |   |   |-- accum_spot_normal_nomsaa.ps
    |   |   |   |-- accum_spot_unshadowed.ps
    |   |   |   |-- accum_spot_unshadowed_msaa.ps
    |   |   |   |-- accum_spot_unshadowed_nomsaa.ps
    |   |   |   |-- accum_sun.ps
    |   |   |   |-- accum_sun.vs
    |   |   |   |-- accum_sun_far.ps
    |   |   |   |-- accum_sun_far_msaa.ps
    |   |   |   |-- accum_sun_far_nomsaa.ps
    |   |   |   |-- accum_sun_mask.ps
    |   |   |   |-- accum_sun_mask_msaa.ps
    |   |   |   |-- accum_sun_mask_nomsaa.ps
    |   |   |   |-- accum_sun_msaa.ps
    |   |   |   |-- accum_sun_near.ps
    |   |   |   |-- accum_sun_near_msaa.ps
    |   |   |   |-- accum_sun_near_msaa_minmax.ps
    |   |   |   |-- accum_sun_near_msaa_nominmax.ps
    |   |   |   |-- accum_sun_near_nomsaa.ps
    |   |   |   |-- accum_sun_near_nomsaa_minmax.ps
    |   |   |   |-- accum_sun_near_nomsaa_nominmax.ps
    |   |   |   |-- accum_sun_near_old.ps
    |   |   |   |-- accum_sun_nomsaa.ps
    |   |   |   |-- accum_volume.vs
    |   |   |   |-- accum_volumetric.ps
    |   |   |   |-- accum_volumetric.vs
    |   |   |   |-- accum_volumetric_msaa.ps
    |   |   |   |-- accum_volumetric_nomsaa.ps
    |   |   |   |-- accum_volumetric_nomsaa.vs
    |   |   |   |-- accum_volumetric_sun.ps
    |   |   |   |-- accum_volumetric_sun_minmax.ps
    |   |   |   |-- accum_volumetric_sun_msaa.ps
    |   |   |   |-- accum_volumetric_sun_msaa0.ps
    |   |   |   |-- accum_volumetric_sun_msaa1.ps
    |   |   |   |-- accum_volumetric_sun_msaa2.ps
    |   |   |   |-- accum_volumetric_sun_msaa3.ps
    |   |   |   |-- accum_volumetric_sun_msaa4.ps
    |   |   |   |-- accum_volumetric_sun_msaa5.ps
    |   |   |   |-- accum_volumetric_sun_msaa6.ps
    |   |   |   |-- accum_volumetric_sun_msaa7.ps
    |   |   |   |-- accum_volumetric_sun_nomsaa.ps
    |   |   |   |-- base_lplanes.ps
    |   |   |   |-- base_lplanes.vs
    |   |   |   |-- bloom_build.ps
    |   |   |   |-- bloom_filter.ps
    |   |   |   |-- bloom_filter_f.ps
    |   |   |   |-- bloom_luminance_1.ps
    |   |   |   |-- bloom_luminance_2.ps
    |   |   |   |-- bloom_luminance_3.ps
    |   |   |   |-- clouds.ps
    |   |   |   |-- clouds.vs
    |   |   |   |-- combine_1.ps
    |   |   |   |-- combine_1.vs
    |   |   |   |-- combine_1_msaa.ps
    |   |   |   |-- combine_1_nomsaa.ps
    |   |   |   |-- combine_2_aa.ps
    |   |   |   |-- combine_2_aa_d.ps
    |   |   |   |-- combine_2_naa.ps
    |   |   |   |-- combine_2_naa_d.ps
    |   |   |   |-- combine_volumetric.ps
    |   |   |   |-- copy.ps
    |   |   |   |-- copy_msaa.ps
    |   |   |   |-- copy_nomsaa.ps
    |   |   |   |-- copy_p.ps
    |   |   |   |-- copy_p_msaa.ps
    |   |   |   |-- copy_p_nomsaa.ps
    |   |   |   |-- create_minmax_sm.ps
    |   |   |   |-- deffer_base_aref_bump-hq.ps
    |   |   |   |-- deffer_base_aref_bump.ps
    |   |   |   |-- deffer_base_aref_bump_d-hq.ps
    |   |   |   |-- deffer_base_aref_bump_d.ps
    |   |   |   |-- deffer_base_aref_bump_db-hq.ps
    |   |   |   |-- deffer_base_aref_flat.ps
    |   |   |   |-- deffer_base_aref_flat_d.ps
    |   |   |   |-- deffer_base_aref_steep-hq.ps
    |   |   |   |-- deffer_base_aref_steep_d-hq.ps
    |   |   |   |-- deffer_base_aref_steep_db-hq.ps
    |   |   |   |-- deffer_base_atoc_aref_bump-hq.ps
    |   |   |   |-- deffer_base_atoc_aref_bump.ps
    |   |   |   |-- deffer_base_atoc_aref_bump_d-hq.ps
    |   |   |   |-- deffer_base_atoc_aref_bump_d.ps
    |   |   |   |-- deffer_base_atoc_aref_bump_db-hq.ps
    |   |   |   |-- deffer_base_atoc_aref_flat.ps
    |   |   |   |-- deffer_base_atoc_aref_flat_d.ps
    |   |   |   |-- deffer_base_atoc_aref_steep-hq.ps
    |   |   |   |-- deffer_base_atoc_aref_steep_d-hq.ps
    |   |   |   |-- deffer_base_atoc_aref_steep_db-hq.ps
    |   |   |   |-- deffer_base_atoc_lmh_aref_bump-hq.ps
    |   |   |   |-- deffer_base_atoc_lmh_aref_bump.ps
    |   |   |   |-- deffer_base_atoc_lmh_aref_bump_d-hq.ps
    |   |   |   |-- deffer_base_atoc_lmh_aref_bump_d.ps
    |   |   |   |-- deffer_base_atoc_lmh_aref_bump_db-hq.ps
    |   |   |   |-- deffer_base_atoc_lmh_aref_flat.ps
    |   |   |   |-- deffer_base_atoc_lmh_aref_flat_d.ps
    |   |   |   |-- deffer_base_atoc_lmh_aref_steep-hq.ps
    |   |   |   |-- deffer_base_atoc_lmh_aref_steep_d-hq.ps
    |   |   |   |-- deffer_base_atoc_lmh_aref_steep_db-hq.ps
    |   |   |   |-- deffer_base_bump-hq.ps
    |   |   |   |-- deffer_base_bump-hq.vs
    |   |   |   |-- deffer_base_bump.ps
    |   |   |   |-- deffer_base_bump.vs
    |   |   |   |-- deffer_base_bump_d-hq.ps
    |   |   |   |-- deffer_base_bump_d-hq.vs
    |   |   |   |-- deffer_base_bump_d.ps
    |   |   |   |-- deffer_base_bump_d.vs
    |   |   |   |-- deffer_base_bump_db-hq.ps
    |   |   |   |-- deffer_base_flat.ps
    |   |   |   |-- deffer_base_flat.vs
    |   |   |   |-- deffer_base_flat_d.ps
    |   |   |   |-- deffer_base_flat_d.vs
    |   |   |   |-- deffer_base_lmh_aref_bump-hq.ps
    |   |   |   |-- deffer_base_lmh_aref_bump.ps
    |   |   |   |-- deffer_base_lmh_aref_bump_d-hq.ps
    |   |   |   |-- deffer_base_lmh_aref_bump_d.ps
    |   |   |   |-- deffer_base_lmh_aref_bump_db-hq.ps
    |   |   |   |-- deffer_base_lmh_aref_flat.ps
    |   |   |   |-- deffer_base_lmh_aref_flat_d.ps
    |   |   |   |-- deffer_base_lmh_aref_steep-hq.ps
    |   |   |   |-- deffer_base_lmh_aref_steep_d-hq.ps
    |   |   |   |-- deffer_base_lmh_aref_steep_db-hq.ps
    |   |   |   |-- deffer_base_lmh_bump-hq.ps
    |   |   |   |-- deffer_base_lmh_bump-hq.vs
    |   |   |   |-- deffer_base_lmh_bump.ps
    |   |   |   |-- deffer_base_lmh_bump.vs
    |   |   |   |-- deffer_base_lmh_bump_d-hq.ps
    |   |   |   |-- deffer_base_lmh_bump_d-hq.vs
    |   |   |   |-- deffer_base_lmh_bump_d.ps
    |   |   |   |-- deffer_base_lmh_bump_d.vs
    |   |   |   |-- deffer_base_lmh_bump_db-hq.ps
    |   |   |   |-- deffer_base_lmh_flat.ps
    |   |   |   |-- deffer_base_lmh_flat.vs
    |   |   |   |-- deffer_base_lmh_flat_d.ps
    |   |   |   |-- deffer_base_lmh_flat_d.vs
    |   |   |   |-- deffer_base_lmh_steep-hq.ps
    |   |   |   |-- deffer_base_lmh_steep_d-hq.ps
    |   |   |   |-- deffer_base_lmh_steep_db-hq.ps
    |   |   |   |-- deffer_base_steep-hq.ps
    |   |   |   |-- deffer_base_steep_d-hq.ps
    |   |   |   |-- deffer_base_steep_db-hq.ps
    |   |   |   |-- deffer_detail_s_flat.vs
    |   |   |   |-- deffer_detail_w_flat.vs
    |   |   |   |-- deffer_impl_flat.ps
    |   |   |   |-- deffer_impl_flat_d.ps
    |   |   |   |-- deffer_impl_flat_d.vs
    |   |   |   |-- deffer_model_bump-hq.vs
    |   |   |   |-- deffer_model_bump.vs
    |   |   |   |-- deffer_model_bump_d-hq.vs
    |   |   |   |-- deffer_model_bump_d.vs
    |   |   |   |-- deffer_model_flat.vs
    |   |   |   |-- deffer_model_flat_d.vs
    |   |   |   |-- deffer_particle.ps
    |   |   |   |-- deffer_particle.vs
    |   |   |   |-- deffer_tree_bump-hq.vs
    |   |   |   |-- deffer_tree_bump.vs
    |   |   |   |-- deffer_tree_bump_d-hq.vs
    |   |   |   |-- deffer_tree_bump_d.vs
    |   |   |   |-- deffer_tree_flat.vs
    |   |   |   |-- deffer_tree_flat_d.vs
    |   |   |   |-- deffer_tree_s_bump-hq.vs
    |   |   |   |-- deffer_tree_s_bump.vs
    |   |   |   |-- deffer_tree_s_bump_d-hq.vs
    |   |   |   |-- deffer_tree_s_bump_d.vs
    |   |   |   |-- deffer_tree_s_flat.vs
    |   |   |   |-- deffer_tree_s_flat_d.vs
    |   |   |   |-- depth_downs.ps
    |   |   |   |-- distort.ps
    |   |   |   |-- dumb.ps
    |   |   |   |-- dumb.vs
    |   |   |   |-- editor.vs
    |   |   |   |-- effects_sun.vs
    |   |   |   |-- effects_wallmark.vs
    |   |   |   |-- fluid_advect.ps
    |   |   |   |-- fluid_advect_bfecc.ps
    |   |   |   |-- fluid_advect_bfecc_temp.ps
    |   |   |   |-- fluid_advect_temp.ps
    |   |   |   |-- fluid_advect_vel.ps
    |   |   |   |-- fluid_advect_vel_g.ps
    |   |   |   |-- fluid_array.gs
    |   |   |   |-- fluid_array_dyn_oobb.gs
    |   |   |   |-- fluid_array_oobb.gs
    |   |   |   |-- fluid_confinement.ps
    |   |   |   |-- fluid_divergence.ps
    |   |   |   |-- fluid_edge_detect.ps
    |   |   |   |-- fluid_edge_detect.vs
    |   |   |   |-- fluid_gaussian.ps
    |   |   |   |-- fluid_grid.vs
    |   |   |   |-- fluid_grid_dyn_oobb.vs
    |   |   |   |-- fluid_grid_oobb.vs
    |   |   |   |-- fluid_jacobi.ps
    |   |   |   |-- fluid_obst_dynamic_oobb.ps
    |   |   |   |-- fluid_obst_static_oobb.ps
    |   |   |   |-- fluid_project.ps
    |   |   |   |-- fluid_raycast_quad.ps
    |   |   |   |-- fluid_raycast_quad.vs
    |   |   |   |-- fluid_raycast_quad_fire.ps
    |   |   |   |-- fluid_raycastcopy_quad.ps
    |   |   |   |-- fluid_raycastcopy_quad_fire.ps
    |   |   |   |-- fluid_raydata_back.ps
    |   |   |   |-- fluid_raydata_back.vs
    |   |   |   |-- fluid_raydata_front.ps
    |   |   |   |-- fluid_raydata_front.vs
    |   |   |   |-- fluid_raydatacopy_quad.ps
    |   |   |   |-- fluid_vorticity.ps
    |   |   |   |-- font2.ps
    |   |   |   |-- hud3d.ps
    |   |   |   |-- hud3d.vs
    |   |   |   |-- hud_crosshair.vs
    |   |   |   |-- hud_font.ps
    |   |   |   |-- lmape.ps
    |   |   |   |-- lmape.vs
    |   |   |   |-- lod.ps
    |   |   |   |-- lod.vs
    |   |   |   |-- mark_msaa_edges.ps
    |   |   |   |-- model_def_lplanes.vs
    |   |   |   |-- model_def_lq.ps
    |   |   |   |-- model_def_lq.vs
    |   |   |   |-- model_distort.vs
    |   |   |   |-- model_distort4ghost.vs
    |   |   |   |-- model_distort4glass.vs
    |   |   |   |-- model_distort_inv.vs
    |   |   |   |-- model_env_lq.ps
    |   |   |   |-- model_env_lq.vs
    |   |   |   |-- particle-clip.vs
    |   |   |   |-- particle.ps
    |   |   |   |-- particle.vs
    |   |   |   |-- particle_alphaonly.ps
    |   |   |   |-- particle_distort.ps
    |   |   |   |-- particle_hard.ps
    |   |   |   |-- particle_s-aadd.ps
    |   |   |   |-- particle_s-add.ps
    |   |   |   |-- particle_s-blend.ps
    |   |   |   |-- portal.ps
    |   |   |   |-- portal.vs
    |   |   |   |-- postprocess.ps
    |   |   |   |-- postprocess_cm.ps
    |   |   |   |-- rain_apply_gloss.ps
    |   |   |   |-- rain_apply_gloss_msaa.ps
    |   |   |   |-- rain_apply_gloss_nomsaa.ps
    |   |   |   |-- rain_apply_normal.ps
    |   |   |   |-- rain_apply_normal_msaa.ps
    |   |   |   |-- rain_apply_normal_nomsaa.ps
    |   |   |   |-- rain_layer.ps
    |   |   |   |-- rain_patch_normal.ps
    |   |   |   |-- rain_patch_normal_msaa.ps
    |   |   |   |-- rain_patch_normal_new.ps
    |   |   |   |-- rain_patch_normal_nomsaa.ps
    |   |   |   |-- shadow_direct_base.ps
    |   |   |   |-- shadow_direct_base.vs
    |   |   |   |-- shadow_direct_base_aref.ps
    |   |   |   |-- shadow_direct_base_aref.vs
    |   |   |   |-- shadow_direct_model.vs
    |   |   |   |-- shadow_direct_model_aref.vs
    |   |   |   |-- shadow_direct_tree.vs
    |   |   |   |-- shadow_direct_tree_aref.vs
    |   |   |   |-- shadow_direct_tree_s.vs
    |   |   |   |-- shadow_direct_tree_s_aref.vs
    |   |   |   |-- simple.ps
    |   |   |   |-- simple_color.ps
    |   |   |   |-- sky2.ps
    |   |   |   |-- sky2.vs
    |   |   |   |-- ssao_calc.ps
    |   |   |   |-- ssao_calc_msaa.ps
    |   |   |   |-- ssao_calc_nomsaa.ps
    |   |   |   |-- stub_default.ps
    |   |   |   |-- stub_default.vs
    |   |   |   |-- stub_default_ma.ps
    |   |   |   |-- stub_notransform.vs
    |   |   |   |-- stub_notransform_2uv.vs
    |   |   |   |-- stub_notransform_aa_aa.vs
    |   |   |   |-- stub_notransform_build.vs
    |   |   |   |-- stub_notransform_filter.vs
    |   |   |   |-- stub_notransform_postpr.vs
    |   |   |   |-- stub_notransform_t.vs
    |   |   |   |-- stub_notransform_t_m2.vs
    |   |   |   |-- stub_notransform_t_m4.vs
    |   |   |   |-- stub_notransform_t_ma.vs
    |   |   |   |-- test.gs
    |   |   |   |-- vert.ps
    |   |   |   |-- vert.vs
    |   |   |   |-- water.ps
    |   |   |   |-- water.vs
    |   |   |   |-- water_soft.ps
    |   |   |   |-- water_soft.vs
    |   |   |   |-- waterd.ps
    |   |   |   |-- waterd.vs
    |   |   |   |-- waterd_soft.ps
    |   |   |   |-- waterd_soft.vs
    |   |   |   |-- wmark.vs
    |   |   |   `-- yuv2rgb.ps
    |   |   `-- r4
    |   |       |-- accum_base.ps
    |   |       |-- accum_emissive.ps
    |   |       |-- accum_emissivel.ps
    |   |       |-- accum_indirect.ps
    |   |       |-- accum_indirect_msaa.ps
    |   |       |-- accum_indirect_nomsaa.ps
    |   |       |-- accum_mask.vs
    |   |       |-- accum_omni_normal.ps
    |   |       |-- accum_omni_normal_msaa.ps
    |   |       |-- accum_omni_normal_nomsaa.ps
    |   |       |-- accum_omni_transluent.ps
    |   |       |-- accum_omni_transluent_msaa.ps
    |   |       |-- accum_omni_transluent_nomsaa.ps
    |   |       |-- accum_omni_unshadowed.ps
    |   |       |-- accum_omni_unshadowed_msaa.ps
    |   |       |-- accum_omni_unshadowed_nomsaa.ps
    |   |       |-- accum_spot_fullsize.ps
    |   |       |-- accum_spot_fullsize_msaa.ps
    |   |       |-- accum_spot_fullsize_nomsaa.ps
    |   |       |-- accum_spot_normal.ps
    |   |       |-- accum_spot_normal_msaa.ps
    |   |       |-- accum_spot_normal_nomsaa.ps
    |   |       |-- accum_spot_unshadowed.ps
    |   |       |-- accum_spot_unshadowed_msaa.ps
    |   |       |-- accum_spot_unshadowed_nomsaa.ps
    |   |       |-- accum_sun.ps
    |   |       |-- accum_sun.vs
    |   |       |-- accum_sun_far.ps
    |   |       |-- accum_sun_far_msaa.ps
    |   |       |-- accum_sun_far_nomsaa.ps
    |   |       |-- accum_sun_mask.ps
    |   |       |-- accum_sun_mask_msaa.ps
    |   |       |-- accum_sun_mask_nomsaa.ps
    |   |       |-- accum_sun_msaa.ps
    |   |       |-- accum_sun_near.ps
    |   |       |-- accum_sun_near_msaa.ps
    |   |       |-- accum_sun_near_msaa_minmax.ps
    |   |       |-- accum_sun_near_msaa_nominmax.ps
    |   |       |-- accum_sun_near_nomsaa.ps
    |   |       |-- accum_sun_near_nomsaa_minmax.ps
    |   |       |-- accum_sun_near_nomsaa_nominmax.ps
    |   |       |-- accum_sun_near_old.ps
    |   |       |-- accum_sun_nomsaa.ps
    |   |       |-- accum_volume.vs
    |   |       |-- accum_volumetric.ps
    |   |       |-- accum_volumetric.vs
    |   |       |-- accum_volumetric_msaa.ps
    |   |       |-- accum_volumetric_nomsaa.ps
    |   |       |-- accum_volumetric_nomsaa.vs
    |   |       |-- accum_volumetric_sun.ps
    |   |       |-- accum_volumetric_sun_minmax.ps
    |   |       |-- accum_volumetric_sun_msaa.ps
    |   |       |-- accum_volumetric_sun_msaa0.ps
    |   |       |-- accum_volumetric_sun_msaa1.ps
    |   |       |-- accum_volumetric_sun_msaa2.ps
    |   |       |-- accum_volumetric_sun_msaa3.ps
    |   |       |-- accum_volumetric_sun_msaa4.ps
    |   |       |-- accum_volumetric_sun_msaa5.ps
    |   |       |-- accum_volumetric_sun_msaa6.ps
    |   |       |-- accum_volumetric_sun_msaa7.ps
    |   |       |-- accum_volumetric_sun_nomsaa.ps
    |   |       |-- base_lplanes.ps
    |   |       |-- base_lplanes.vs
    |   |       |-- bloom_build.ps
    |   |       |-- bloom_filter.ps
    |   |       |-- bloom_filter_f.ps
    |   |       |-- bloom_luminance_1.ps
    |   |       |-- bloom_luminance_2.ps
    |   |       |-- bloom_luminance_3.ps
    |   |       |-- clouds.ps
    |   |       |-- clouds.vs
    |   |       |-- combine_1.ps
    |   |       |-- combine_1.vs
    |   |       |-- combine_1_msaa.ps
    |   |       |-- combine_1_nomsaa.ps
    |   |       |-- combine_2_aa.ps
    |   |       |-- combine_2_aa_d.ps
    |   |       |-- combine_2_naa.ps
    |   |       |-- combine_2_naa_d.ps
    |   |       |-- combine_volumetric.ps
    |   |       |-- copy.ps
    |   |       |-- copy_msaa.ps
    |   |       |-- copy_nomsaa.ps
    |   |       |-- copy_p.ps
    |   |       |-- copy_p_msaa.ps
    |   |       |-- copy_p_nomsaa.ps
    |   |       |-- create_minmax_sm.ps
    |   |       |-- deffer_base_aref_bump-hq.ps
    |   |       |-- deffer_base_aref_bump.ps
    |   |       |-- deffer_base_aref_bump_d-hq.ps
    |   |       |-- deffer_base_aref_bump_d.ps
    |   |       |-- deffer_base_aref_bump_db-hq.ps
    |   |       |-- deffer_base_aref_flat.ps
    |   |       |-- deffer_base_aref_flat_d.ps
    |   |       |-- deffer_base_aref_steep-hq.ps
    |   |       |-- deffer_base_aref_steep_d-hq.ps
    |   |       |-- deffer_base_aref_steep_db-hq.ps
    |   |       |-- deffer_base_atoc_aref_bump-hq.ps
    |   |       |-- deffer_base_atoc_aref_bump.ps
    |   |       |-- deffer_base_atoc_aref_bump_d-hq.ps
    |   |       |-- deffer_base_atoc_aref_bump_d.ps
    |   |       |-- deffer_base_atoc_aref_bump_db-hq.ps
    |   |       |-- deffer_base_atoc_aref_flat.ps
    |   |       |-- deffer_base_atoc_aref_flat_d.ps
    |   |       |-- deffer_base_atoc_aref_steep-hq.ps
    |   |       |-- deffer_base_atoc_aref_steep_d-hq.ps
    |   |       |-- deffer_base_atoc_aref_steep_db-hq.ps
    |   |       |-- deffer_base_atoc_lmh_aref_bump-hq.ps
    |   |       |-- deffer_base_atoc_lmh_aref_bump.ps
    |   |       |-- deffer_base_atoc_lmh_aref_bump_d-hq.ps
    |   |       |-- deffer_base_atoc_lmh_aref_bump_d.ps
    |   |       |-- deffer_base_atoc_lmh_aref_bump_db-hq.ps
    |   |       |-- deffer_base_atoc_lmh_aref_flat.ps
    |   |       |-- deffer_base_atoc_lmh_aref_flat_d.ps
    |   |       |-- deffer_base_atoc_lmh_aref_steep-hq.ps
    |   |       |-- deffer_base_atoc_lmh_aref_steep_d-hq.ps
    |   |       |-- deffer_base_atoc_lmh_aref_steep_db-hq.ps
    |   |       |-- deffer_base_bump-hq.ps
    |   |       |-- deffer_base_bump-hq.vs
    |   |       |-- deffer_base_bump.ps
    |   |       |-- deffer_base_bump.vs
    |   |       |-- deffer_base_bump_d-hq.ps
    |   |       |-- deffer_base_bump_d-hq.vs
    |   |       |-- deffer_base_bump_d.ps
    |   |       |-- deffer_base_bump_d.vs
    |   |       |-- deffer_base_bump_db-hq.ps
    |   |       |-- deffer_base_flat.ps
    |   |       |-- deffer_base_flat.vs
    |   |       |-- deffer_base_flat_d.ps
    |   |       |-- deffer_base_flat_d.vs
    |   |       |-- deffer_base_lmh_aref_bump-hq.ps
    |   |       |-- deffer_base_lmh_aref_bump.ps
    |   |       |-- deffer_base_lmh_aref_bump_d-hq.ps
    |   |       |-- deffer_base_lmh_aref_bump_d.ps
    |   |       |-- deffer_base_lmh_aref_bump_db-hq.ps
    |   |       |-- deffer_base_lmh_aref_flat.ps
    |   |       |-- deffer_base_lmh_aref_flat_d.ps
    |   |       |-- deffer_base_lmh_aref_steep-hq.ps
    |   |       |-- deffer_base_lmh_aref_steep_d-hq.ps
    |   |       |-- deffer_base_lmh_aref_steep_db-hq.ps
    |   |       |-- deffer_base_lmh_bump-hq.ps
    |   |       |-- deffer_base_lmh_bump-hq.vs
    |   |       |-- deffer_base_lmh_bump.ps
    |   |       |-- deffer_base_lmh_bump.vs
    |   |       |-- deffer_base_lmh_bump_d-hq.ps
    |   |       |-- deffer_base_lmh_bump_d-hq.vs
    |   |       |-- deffer_base_lmh_bump_d.ps
    |   |       |-- deffer_base_lmh_bump_d.vs
    |   |       |-- deffer_base_lmh_bump_db-hq.ps
    |   |       |-- deffer_base_lmh_flat.ps
    |   |       |-- deffer_base_lmh_flat.vs
    |   |       |-- deffer_base_lmh_flat_d.ps
    |   |       |-- deffer_base_lmh_flat_d.vs
    |   |       |-- deffer_base_lmh_steep-hq.ps
    |   |       |-- deffer_base_lmh_steep_d-hq.ps
    |   |       |-- deffer_base_lmh_steep_db-hq.ps
    |   |       |-- deffer_base_steep-hq.ps
    |   |       |-- deffer_base_steep_d-hq.ps
    |   |       |-- deffer_base_steep_db-hq.ps
    |   |       |-- deffer_detail_s_flat.vs
    |   |       |-- deffer_detail_w_flat.vs
    |   |       |-- deffer_impl_flat.ps
    |   |       |-- deffer_impl_flat_d.ps
    |   |       |-- deffer_impl_flat_d.vs
    |   |       |-- deffer_model_bump-hq.vs
    |   |       |-- deffer_model_bump.vs
    |   |       |-- deffer_model_bump_d-hq.vs
    |   |       |-- deffer_model_bump_d.vs
    |   |       |-- deffer_model_flat.vs
    |   |       |-- deffer_model_flat_d.vs
    |   |       |-- deffer_particle.ps
    |   |       |-- deffer_particle.vs
    |   |       |-- deffer_tree_bump-hq.vs
    |   |       |-- deffer_tree_bump.vs
    |   |       |-- deffer_tree_bump_d-hq.vs
    |   |       |-- deffer_tree_bump_d.vs
    |   |       |-- deffer_tree_flat.vs
    |   |       |-- deffer_tree_flat_d.vs
    |   |       |-- deffer_tree_s_bump-hq.vs
    |   |       |-- deffer_tree_s_bump.vs
    |   |       |-- deffer_tree_s_bump_d-hq.vs
    |   |       |-- deffer_tree_s_bump_d.vs
    |   |       |-- deffer_tree_s_flat.vs
    |   |       |-- deffer_tree_s_flat_d.vs
    |   |       |-- depth_downs.ps
    |   |       |-- distort.ps
    |   |       |-- dumb.ps
    |   |       |-- dumb.vs
    |   |       |-- editor.vs
    |   |       |-- effects_sun.vs
    |   |       |-- effects_wallmark.vs
    |   |       |-- fluid_advect.ps
    |   |       |-- fluid_advect_bfecc.ps
    |   |       |-- fluid_advect_bfecc_temp.ps
    |   |       |-- fluid_advect_temp.ps
    |   |       |-- fluid_advect_vel.ps
    |   |       |-- fluid_advect_vel_g.ps
    |   |       |-- fluid_array.gs
    |   |       |-- fluid_array_dyn_oobb.gs
    |   |       |-- fluid_array_oobb.gs
    |   |       |-- fluid_confinement.ps
    |   |       |-- fluid_divergence.ps
    |   |       |-- fluid_edge_detect.ps
    |   |       |-- fluid_edge_detect.vs
    |   |       |-- fluid_gaussian.ps
    |   |       |-- fluid_grid.vs
    |   |       |-- fluid_grid_dyn_oobb.vs
    |   |       |-- fluid_grid_oobb.vs
    |   |       |-- fluid_jacobi.ps
    |   |       |-- fluid_obst_dynamic_oobb.ps
    |   |       |-- fluid_obst_static_oobb.ps
    |   |       |-- fluid_project.ps
    |   |       |-- fluid_raycast_quad.ps
    |   |       |-- fluid_raycast_quad.vs
    |   |       |-- fluid_raycast_quad_fire.ps
    |   |       |-- fluid_raycastcopy_quad.ps
    |   |       |-- fluid_raycastcopy_quad_fire.ps
    |   |       |-- fluid_raydata_back.ps
    |   |       |-- fluid_raydata_back.vs
    |   |       |-- fluid_raydata_front.ps
    |   |       |-- fluid_raydata_front.vs
    |   |       |-- fluid_raydatacopy_quad.ps
    |   |       |-- fluid_vorticity.ps
    |   |       |-- font2.ps
    |   |       |-- hud3d.ps
    |   |       |-- hud3d.vs
    |   |       |-- hud_crosshair.vs
    |   |       |-- hud_font.ps
    |   |       |-- lmape.ps
    |   |       |-- lmape.vs
    |   |       |-- lod.ps
    |   |       |-- lod.vs
    |   |       |-- mark_msaa_edges.ps
    |   |       |-- model_def_lplanes.vs
    |   |       |-- model_def_lq.ps
    |   |       |-- model_def_lq.vs
    |   |       |-- model_distort.vs
    |   |       |-- model_distort4ghost.vs
    |   |       |-- model_distort4glass.vs
    |   |       |-- model_distort_inv.vs
    |   |       |-- model_env_lq.ps
    |   |       |-- model_env_lq.vs
    |   |       |-- particle-clip.vs
    |   |       |-- particle.ps
    |   |       |-- particle.vs
    |   |       |-- particle_alphaonly.ps
    |   |       |-- particle_distort.ps
    |   |       |-- particle_hard.ps
    |   |       |-- particle_s-aadd.ps
    |   |       |-- particle_s-add.ps
    |   |       |-- particle_s-blend.ps
    |   |       |-- portal.ps
    |   |       |-- portal.vs
    |   |       |-- postprocess.ps
    |   |       |-- postprocess_cm.ps
    |   |       |-- rain_apply_gloss.ps
    |   |       |-- rain_apply_gloss_msaa.ps
    |   |       |-- rain_apply_gloss_nomsaa.ps
    |   |       |-- rain_apply_normal.ps
    |   |       |-- rain_apply_normal_msaa.ps
    |   |       |-- rain_apply_normal_nomsaa.ps
    |   |       |-- rain_layer.ps
    |   |       |-- rain_patch_normal.ps
    |   |       |-- rain_patch_normal_msaa.ps
    |   |       |-- rain_patch_normal_new.ps
    |   |       |-- rain_patch_normal_nomsaa.ps
    |   |       |-- shadow_direct_base.ps
    |   |       |-- shadow_direct_base.vs
    |   |       |-- shadow_direct_base_aref.ps
    |   |       |-- shadow_direct_base_aref.vs
    |   |       |-- shadow_direct_model.vs
    |   |       |-- shadow_direct_model_aref.vs
    |   |       |-- shadow_direct_tree.vs
    |   |       |-- shadow_direct_tree_aref.vs
    |   |       |-- shadow_direct_tree_s.vs
    |   |       |-- shadow_direct_tree_s_aref.vs
    |   |       |-- simple.ps
    |   |       |-- simple_color.ps
    |   |       |-- sky2.ps
    |   |       |-- sky2.vs
    |   |       |-- ssao_calc.ps
    |   |       |-- ssao_calc_msaa.ps
    |   |       |-- ssao_calc_nomsaa.ps
    |   |       |-- ssao_hdao.cs
    |   |       |-- ssao_hdao_msaa.cs
    |   |       |-- stub_default.ps
    |   |       |-- stub_default.vs
    |   |       |-- stub_default_ma.ps
    |   |       |-- stub_notransform.vs
    |   |       |-- stub_notransform_2uv.vs
    |   |       |-- stub_notransform_aa_aa.vs
    |   |       |-- stub_notransform_build.vs
    |   |       |-- stub_notransform_filter.vs
    |   |       |-- stub_notransform_postpr.vs
    |   |       |-- stub_notransform_t.vs
    |   |       |-- stub_notransform_t_m2.vs
    |   |       |-- stub_notransform_t_m4.vs
    |   |       |-- stub_notransform_t_ma.vs
    |   |       |-- tess.ds
    |   |       |-- tess.hs
    |   |       |-- tess_shadow.ds
    |   |       |-- test.gs
    |   |       |-- vert.ps
    |   |       |-- vert.vs
    |   |       |-- water.ps
    |   |       |-- water.vs
    |   |       |-- water_soft.ps
    |   |       |-- water_soft.vs
    |   |       |-- waterd.ps
    |   |       |-- waterd.vs
    |   |       |-- waterd_soft.ps
    |   |       |-- waterd_soft.vs
    |   |       |-- wmark.vs
    |   |       `-- yuv2rgb.ps
    |   `-- shared
    `-- shared
```

<a id="spawns"></a>

### spawns.db

```console
`-- spawns
```

<a id="xr"></a>

### xr.db

```console
0 directories
```

## maps - directory

<a id="fake_start"></a>

### fake_start.db

```console
`-- levels
    `-- fake_start
```

<a id="jupiter"></a>

### jupiter.db

```console
`-- levels
    `-- jupiter
        |-- meshes
        `-- terrain
```

<a id="jupiter_underground"></a>

### jupiter_underground.db

```console
`-- levels
    `-- jupiter_underground
        `-- meshes
```

<a id="k00_marsh"></a>

### k00_marsh.db

```console
`-- levels
    `-- k00_marsh
        |-- meshes
        `-- terrain
```

<a id="k01_darkscape"></a>

### k01_darkscape.db

```console
`-- levels
    `-- k01_darkscape
        `-- terrain
```

<a id="k02_trucks_cemetery"></a>

### k02_trucks_cemetery.db

```console
`-- levels
    `-- k02_trucks_cemetery
        |-- meshes
        `-- terrain
```

<a id="l01_escape"></a>

### l01_escape.db

```console
`-- levels
    `-- l01_escape
        |-- meshes
        `-- terrain
```

<a id="l02_garbage"></a>

### l02_garbage.db

```console
`-- levels
    `-- l02_garbage
        |-- meshes
        `-- terrain
```

<a id="l03_agroprom"></a>

### l03_agroprom.db

```console
`-- levels
    `-- l03_agroprom
        `-- terrain
```

<a id="l03u_agr_underground"></a>

### l03u_agr_underground.db

```console
`-- levels
    `-- l03u_agr_underground
```

<a id="l04_darkvalley"></a>

### l04_darkvalley.db

```console
`-- levels
    `-- l04_darkvalley
        |-- meshes
        `-- terrain
```

<a id="l04u_labx18"></a>

### l04u_labx18.db

```console
`-- levels
    `-- l04u_labx18
        `-- meshes
```

<a id="l05_bar"></a>

### l05_bar.db

```console
`-- levels
    `-- l05_bar
        `-- terrain
```

<a id="l06_rostok"></a>

### l06_rostok.db

```console
`-- levels
    `-- l06_rostok
        |-- meshes
        `-- terrain
```

<a id="l07_military"></a>

### l07_military.db

```console
`-- levels
    `-- l07_military
        |-- meshes
        `-- terrain
```

<a id="l08_yantar"></a>

### l08_yantar.db

```console
`-- levels
    `-- l08_yantar
        |-- meshes
        `-- terrain
```

<a id="l08u_brainlab"></a>

### l08u_brainlab.db

```console
`-- levels
    `-- l08u_brainlab
        `-- meshes
```

<a id="l09_deadcity"></a>

### l09_deadcity.db

```console
`-- levels
    `-- l09_deadcity
        |-- meshes
        `-- terrain
```

<a id="l10_limansk"></a>

### l10_limansk.db

```console
`-- levels
    `-- l10_limansk
        |-- meshes
        `-- terrain
```

<a id="l10_radar"></a>

### l10_radar.db

```console
`-- levels
    `-- l10_radar
        |-- meshes
        `-- terrain
```

<a id="l10_red_forest"></a>

### l10_red_forest.db

```console
`-- levels
    `-- l10_red_forest
        |-- meshes
        `-- terrain
```

<a id="l10u_bunker"></a>

### l10u_bunker.db

```console
`-- levels
    `-- l10u_bunker
```

<a id="l11_hospital"></a>

### l11_hospital.db

```console
`-- levels
    `-- l11_hospital
        `-- terrain
```

<a id="l11_pripyat"></a>

### l11_pripyat.db

```console
`-- levels
    `-- l11_pripyat
        |-- meshes
        `-- terrain
```

<a id="l12_stancia"></a>

### l12_stancia.db

```console
`-- levels
    `-- l12_stancia
        |-- meshes
        `-- terrain
```

<a id="l12_stancia_2"></a>

### l12_stancia_2.db

```console
`-- levels
    `-- l12_stancia_2
        |-- meshes
        `-- terrain
```

<a id="l12u_control_monolith"></a>

### l12u_control_monolith.db

```console
`-- levels
    `-- l12u_control_monolith
```

<a id="l12u_sarcofag"></a>

### l12u_sarcofag.db

```console
`-- levels
    `-- l12u_sarcofag
```

<a id="l13_generators"></a>

### l13_generators.db

```console
`-- levels
    `-- l13_generators
        |-- meshes
        `-- terrain
```

<a id="l13u_warlab"></a>

### l13u_warlab.db

```console
`-- levels
    `-- l13u_warlab
        `-- meshes
```

<a id="labx8"></a>

### labx8.db

```console
`-- levels
    `-- labx8
```

<a id="pripyat"></a>

### pripyat.db

```console
`-- levels
    `-- pripyat
        |-- meshes
        `-- terrain
```

<a id="zaton"></a>

### zaton.db

```console
`-- levels
    `-- zaton
        |-- meshes
        `-- terrain
```

## patch - directory

<a id="xpatch_meshes"></a>

### xpatch_meshes.db

```console
`-- meshes
    `-- monsters
        `-- controller
```

<a id="xpatch_sounds"></a>

### xpatch_sounds.db

```console
`-- sounds
    `-- characters_voice
        |-- human_01
        |   |-- ecolog
        |   |   `-- states
        |   |       `-- meet
        |   |-- killer
        |   |   `-- states
        |   |       `-- meet
        |   `-- newbie
        |       `-- states
        |           `-- meet
        |-- human_02
        |   |-- ecolog
        |   |   `-- states
        |   |       `-- meet
        |   |-- killer
        |   |   `-- states
        |   |       `-- meet
        |   `-- newbie
        |       `-- states
        |           `-- meet
        `-- human_03
            |-- ecolog
            |   `-- states
            |       `-- meet
            |-- killer
            |   `-- states
            |       `-- meet
            `-- newbie
                `-- states
                    `-- meet
```

<a id="xpatch_textures"></a>

### xpatch_textures.db

```console
`-- textures
    |-- act
    |-- crete
    |-- ed
    |-- item
    |-- map
    |-- mtl
    |-- ston
    |-- ui
    `-- wpn
```

## resource - directory

<a id="meshes0"></a>

### meshes.db0

```console
`-- meshes
    |-- actors
    |   |-- barman
    |   |-- dolg
    |   |-- izgoy
    |   |-- neytral
    |   |-- stalker_bandit
    |   |-- stalker_dolg
    |   |-- stalker_ecologist
    |   |-- stalker_freedom
    |   |-- stalker_hero
    |   |-- stalker_invisible
    |   |-- stalker_lesnik
    |   |-- stalker_merc
    |   |-- stalker_monolith
    |   |-- stalker_nebo
    |   |-- stalker_neutral
    |   |-- stalker_osoznanie
    |   |-- stalker_soldier
    |   |-- stalker_trader
    |   |-- stalker_ucheniy
    |   |-- stalker_zombied
    |   `-- ucheniy
    |-- dm
    |-- dynamics
    |   |-- anomaly
    |   |-- armory_room
    |   |-- artefacts
    |   |-- balon
    |   |-- box
    |   |   |-- part
    |   |   `-- prt
    |   |-- dead_body
    |   |-- decor
    |   |-- devices
    |   |   |-- dev_antirad
    |   |   |-- dev_aptechka
    |   |   |-- dev_artefact
    |   |   |-- dev_bandage
    |   |   |-- dev_binoculars
    |   |   |-- dev_bolt
    |   |   |-- dev_bred
    |   |   |-- dev_conserv
    |   |   |-- dev_datchik
    |   |   |-- dev_datchik_1
    |   |   |-- dev_datchik_2
    |   |   |-- dev_datchik_3
    |   |   |-- dev_decoder
    |   |   |-- dev_detector_1
    |   |   |-- dev_detector_2
    |   |   |-- dev_detector_3
    |   |   |-- dev_detector_4
    |   |   |-- dev_drink_stalker
    |   |   |-- dev_flare
    |   |   |-- dev_flash_1
    |   |   |-- dev_flash_2
    |   |   |-- dev_fmradio
    |   |   |-- dev_guitar
    |   |   |-- dev_harmonica
    |   |   |-- dev_instrument_1
    |   |   |-- dev_kolbasa
    |   |   |-- dev_merger
    |   |   |-- dev_pda
    |   |   |-- dev_rukzak
    |   |   |-- dev_torch_light
    |   |   `-- dev_vodka
    |   |-- door
    |   |   |-- part
    |   |   `-- prt
    |   |-- el_tehnika
    |   |-- equipment_cache
    |   |-- equipments
    |   |   |-- medical
    |   |   `-- quest
    |   |-- fence
    |   |   `-- part
    |   |-- firestation
    |   |-- keyboard
    |   |-- kitchen_room
    |   |   `-- part
    |   |-- large_trash
    |   |   `-- prt
    |   |-- light
    |   |-- medical_object
    |   |-- outfit
    |   |-- rope
    |   |-- scene_objects
    |   |   |-- darkvalley
    |   |   |-- hospital
    |   |   |   `-- part
    |   |   |-- labx8
    |   |   |-- part
    |   |   |-- pripyat
    |   |   |   `-- part
    |   |   `-- red_forest
    |   |-- small_trash
    |   |   `-- prt
    |   |-- stol
    |   |-- stul
    |   |-- technica
    |   |-- tfw_badges
    |   |-- vehicles
    |   |   |-- btr
    |   |   |-- mi2
    |   |   |   `-- part
    |   |   |-- mi24
    |   |   |   `-- part
    |   |   |-- veh_baggi
    |   |   |-- veh_btr
    |   |   |   `-- part
    |   |   |-- veh_gaz66
    |   |   |-- veh_kamaz
    |   |   |-- veh_kavz
    |   |   |-- veh_laz
    |   |   |-- veh_moskvich
    |   |   |-- veh_niva
    |   |   |-- veh_tr13
    |   |   |-- veh_uaz
    |   |   |   `-- part
    |   |   |-- veh_uaz_buhanka
    |   |   |-- veh_zaz
    |   |   |   `-- part
    |   |   |-- veh_zaz_968
    |   |   |   `-- part
    |   |   |-- veh_zil_130
    |   |   `-- veh_zil_131
    |   |-- weapons
    |   |   |-- wpn_abakan
    |   |   |-- wpn_ak74
    |   |   |-- wpn_ak74u
    |   |   |-- wpn_ammo
    |   |   |-- wpn_artefact
    |   |   |-- wpn_beretta92fs
    |   |   |-- wpn_bm16
    |   |   |-- wpn_colt1911
    |   |   |-- wpn_desert_eagle
    |   |   |-- wpn_fn2000
    |   |   |-- wpn_fort
    |   |   |-- wpn_g36
    |   |   |-- wpn_gauss
    |   |   |-- wpn_grenades
    |   |   |-- wpn_groza
    |   |   |-- wpn_hand
    |   |   |-- wpn_hpsa
    |   |   |-- wpn_knife
    |   |   |-- wpn_l85
    |   |   |-- wpn_lr300
    |   |   |-- wpn_mine
    |   |   |-- wpn_mounted
    |   |   |-- wpn_mp5
    |   |   |-- wpn_pb
    |   |   |-- wpn_pfm1
    |   |   |-- wpn_pkm
    |   |   |-- wpn_pm
    |   |   |-- wpn_protecta
    |   |   |-- wpn_rg6
    |   |   |-- wpn_rpg7
    |   |   |-- wpn_sig220
    |   |   |-- wpn_sig550
    |   |   |-- wpn_spas12
    |   |   |-- wpn_svd
    |   |   |-- wpn_svu
    |   |   |-- wpn_toz34
    |   |   |-- wpn_upgrade
    |   |   |-- wpn_usp45
    |   |   |-- wpn_val
    |   |   |-- wpn_vintorez
    |   |   |-- wpn_walter99
    |   |   `-- wpn_winchester1300
    |   |-- wood_doski
    |   |-- workshop_room
    |   `-- zpf
    |-- equipments
    |-- grenadier
    `-- monsters
        |-- borya
        |-- burer
        |-- cat
        |-- chimera
        |-- controller
        |-- crow
        |-- dog
        |-- flesh
        |-- izlom
        |-- krovosos
        |-- mutant_boar
        |-- phantom
        |-- poltergeist
        |-- pseudodog
        |-- psevdogigant
        |-- rat
        |-- snork
        |-- tushkano
        `-- zombi
```

<a id="meshes1"></a>

### meshes.db1

```console
`-- meshes
    `-- monsters
        |-- snork
        |-- tushkano
        `-- zombi
```

<a id="textures0"></a>

### textures.db0

```console
`-- textures
    |-- act
    |   |-- eye
    |   |-- face
    |   `-- variation mod
    |       `-- act_neutral
    |-- artifact
    |-- briks
    |-- controller
    |-- corp
    |-- crete
    |-- decal
    |-- detail
    |-- door
    |-- ed
    |-- effects
    |-- fbr
    |-- flare
    |-- floor
    |-- food
    |-- fx
    |-- glas
    |-- glass
    |-- glow
    |-- grad
    |-- grenadier
    |-- grnd
    |-- hud
    |-- internal
    |-- intro
    |-- item
    |-- lights
    |-- lod
    |-- map
    |-- mtl
    |-- mutantparts
    |-- pfx
    |   `-- r_pop
    |       `-- shells
    |-- prop
    |-- roof
    |-- shoker_mod
    |   |-- explosions
    |   |-- pfx
    |   `-- wpn
    |       `-- axe
    |-- sign
    |-- sky
    |   |-- af1_cloudy
    |   |-- af1_foggy
    |   |-- af3_blowout
    |   |-- af3_clear
    |   |-- af3_cloudy
    |   |-- af3_foggy
    |   |-- af3_partly
    |   `-- af3_rainy
    |-- ston
    |-- terrain
    |-- tile
    |-- tree
    |-- trees
    |-- ui
    |-- veh
    |-- vehicle
    |-- vine
    |-- wall
    |-- water
    |-- wind
    |-- wm
    |-- wood
    `-- wpn
```

<a id="textures1"></a>

### textures.db1

```console
`-- textures
    |-- crete
    |-- decal
    |-- detail
    |-- door
    |-- ed
    |-- effects
    |-- fbr
    |-- flare
    |-- floor
    |-- food
    |-- fx
    |-- glas
    |-- glass
    |-- glow
    |-- grad
    |-- grenadier
    |-- grnd
    |-- hud
    |-- internal
    |-- intro
    |-- item
    |-- lights
    |-- map
    |-- mtl
    |-- mutantparts
    |-- pfx
    |   `-- r_pop
    |       `-- shells
    `-- prop
```

<a id="textures2"></a>

### textures.db2

```console
`-- textures
    |-- prop
    |-- roof
    |-- shoker_mod
    |   |-- explosions
    |   `-- pfx
    |-- sign
    |-- sky
    |   |-- af1_cloudy
    |   |-- af1_foggy
    |   |-- af3_blowout
    |   |-- af3_clear
    |   |-- af3_cloudy
    |   |-- af3_foggy
    |   |-- af3_partly
    |   `-- af3_rainy
    |-- ston
    |-- terrain
    |-- tile
    |-- tree
    |-- trees
    |-- ui
    `-- veh
```

<a id="textures3"></a>

### textures.db3

```console
`-- textures
    |-- veh
    |-- vehicle
    |-- vine
    |-- wall
    |-- water
    |-- wind
    |-- wm
    |-- wood
    `-- wpn
```

## sound - directory

<a id="sounds"></a>

### sounds.db

```console
`-- sounds
    |-- actor
    |-- affects
    |-- ambient
    |   |-- arena
    |   |-- background
    |   |-- bar
    |   |-- blowout
    |   |-- indoors
    |   |-- jupiter
    |   |-- labx8
    |   |-- megaphones
    |   |-- mine
    |   |-- outdoors
    |   |-- pripyat
    |   |-- rnd_outdoor
    |   |-- special
    |   |-- tuman
    |   |-- ugrnd
    |   |-- underground
    |   |-- underpass
    |   |-- x16
    |   |-- x18
    |   `-- zaton
    |-- anomaly
    |-- car
    |   |-- veh_kamaz
    |   |-- veh_laz
    |   |-- veh_niva
    |   |-- veh_uaz
    |   |-- veh_zaz
    |   `-- veh_zil
    |-- characters_voice
    |   |-- dialogs
    |   |-- human_01
    |   |   |-- bandit
    |   |   |   |-- alife
    |   |   |   |   |-- attack
    |   |   |   |   |-- counter_attack
    |   |   |   |   |-- defence
    |   |   |   |   `-- patrol
    |   |   |   |-- fight
    |   |   |   |   |-- attack
    |   |   |   |   |-- backup
    |   |   |   |   |-- cover_fire
    |   |   |   |   |-- death
    |   |   |   |   |-- detour
    |   |   |   |   |-- enemy
    |   |   |   |   |-- friend_hitted
    |   |   |   |   |-- friendly_fire
    |   |   |   |   |-- friendly_grenade
    |   |   |   |   |-- grenade
    |   |   |   |   |-- hit
    |   |   |   |   |-- post_combat_wait
    |   |   |   |   |-- searching_enemy
    |   |   |   |   `-- tolls
    |   |   |   |-- hail
    |   |   |   |-- help
    |   |   |   |   |-- not_wounded
    |   |   |   |   |-- wounded
    |   |   |   |   |-- wounded_heavy
    |   |   |   |   |-- wounded_not_see_helper
    |   |   |   |   |-- wounded_psy
    |   |   |   |   |-- wounded_see_helper
    |   |   |   |   `-- wounded_thanx
    |   |   |   |-- music
    |   |   |   |-- reactions
    |   |   |   |   |-- joke
    |   |   |   |   |-- music
    |   |   |   |   `-- story
    |   |   |   |-- states
    |   |   |   |   |-- breath
    |   |   |   |   |-- idle
    |   |   |   |   |-- loot
    |   |   |   |   |-- meet
    |   |   |   |   |-- panic_human
    |   |   |   |   |-- panic_monster
    |   |   |   |   `-- sleep
    |   |   |   |-- talk
    |   |   |   |   |-- intros
    |   |   |   |   |-- jokes
    |   |   |   |   `-- use
    |   |   |   `-- threat
    |   |   |       |-- back_off
    |   |   |       `-- drop_weapon
    |   |   |-- csky
    |   |   |   |-- alife
    |   |   |   |   |-- attack
    |   |   |   |   |-- counter_attack
    |   |   |   |   |-- defence
    |   |   |   |   `-- patrol
    |   |   |   |-- fight
    |   |   |   |   |-- attack
    |   |   |   |   |-- backup
    |   |   |   |   |-- cover_fire
    |   |   |   |   |-- death
    |   |   |   |   |-- detour
    |   |   |   |   |-- enemy
    |   |   |   |   |-- enemy_down
    |   |   |   |   |-- enemy_hit
    |   |   |   |   |-- fire
    |   |   |   |   |-- friend_hitted
    |   |   |   |   |-- friendly_fire
    |   |   |   |   |-- grenade
    |   |   |   |   |-- hit
    |   |   |   |   |-- post_combat_wait
    |   |   |   |   |-- searching_enemy
    |   |   |   |   |-- threat
    |   |   |   |   `-- tolls
    |   |   |   |-- help
    |   |   |   |   |-- wounded
    |   |   |   |   |-- wounded_heavy
    |   |   |   |   `-- wounded_thanx
    |   |   |   |-- music
    |   |   |   |-- reactions
    |   |   |   |   |-- box
    |   |   |   |   |-- joke
    |   |   |   |   |-- music
    |   |   |   |   `-- story
    |   |   |   |-- states
    |   |   |   |   |-- breath
    |   |   |   |   |-- idle
    |   |   |   |   |-- loot
    |   |   |   |   |-- meet
    |   |   |   |   |-- panic_human
    |   |   |   |   |-- panic_monster
    |   |   |   |   `-- sleep
    |   |   |   |-- talk
    |   |   |   |   |-- intros
    |   |   |   |   |-- jokes
    |   |   |   |   `-- use
    |   |   |   `-- threat
    |   |   |       |-- back_off
    |   |   |       `-- drop_weapon
    |   |   |-- dolg
    |   |   |   |-- alife
    |   |   |   |   |-- attack
    |   |   |   |   |-- counter_attack
    |   |   |   |   |-- defence
    |   |   |   |   `-- patrol
    |   |   |   |-- fight
    |   |   |   |   |-- attack
    |   |   |   |   |-- backup
    |   |   |   |   |-- cover_fire
    |   |   |   |   |-- death
    |   |   |   |   |-- detour
    |   |   |   |   |-- enemy
    |   |   |   |   |-- enemy_down
    |   |   |   |   |-- enemy_hit
    |   |   |   |   |-- fire
    |   |   |   |   |-- friend_hitted
    |   |   |   |   |-- friendly_fire
    |   |   |   |   |-- friendly_grenade
    |   |   |   |   |-- grenade
    |   |   |   |   |-- hit
    |   |   |   |   |-- post_combat_wait
    |   |   |   |   |-- searching_enemy
    |   |   |   |   |-- threat
    |   |   |   |   `-- tolls
    |   |   |   |-- hail
    |   |   |   |-- help
    |   |   |   |   |-- combat
    |   |   |   |   |-- not_wounded
    |   |   |   |   |-- wounded
    |   |   |   |   |-- wounded_heavy
    |   |   |   |   |-- wounded_not_see_helper
    |   |   |   |   |-- wounded_psy
    |   |   |   |   |-- wounded_see_helper
    |   |   |   |   `-- wounded_thanx
    |   |   |   |-- music
    |   |   |   |-- reactions
    |   |   |   |   |-- box
    |   |   |   |   |-- joke
    |   |   |   |   |-- music
    |   |   |   |   `-- story
    |   |   |   |-- states
    |   |   |   |   |-- breath
    |   |   |   |   |-- idle
    |   |   |   |   |-- loot
    |   |   |   |   |-- meet
    |   |   |   |   |-- panic_human
    |   |   |   |   |-- panic_monster
    |   |   |   |   |-- sleep
    |   |   |   |   `-- trade
    |   |   |   |-- talk
    |   |   |   |   |-- intros
    |   |   |   |   |-- jokes
    |   |   |   |   `-- use
    |   |   |   `-- threat
    |   |   |       |-- back_off
    |   |   |       `-- drop_weapon
    |   |   |-- ecolog
    |   |   |   |-- fight
    |   |   |   |   |-- attack
    |   |   |   |   |-- backup
    |   |   |   |   |-- cover_fire
    |   |   |   |   |-- danger_sound
    |   |   |   |   |-- death
    |   |   |   |   |-- detour
    |   |   |   |   |-- enemy
    |   |   |   |   |-- enemy_down
    |   |   |   |   |-- enemy_hit
    |   |   |   |   |-- fire
    |   |   |   |   |-- friend_hitted
    |   |   |   |   |-- friendly_fire
    |   |   |   |   |-- friendly_grenade
    |   |   |   |   |-- grenade
    |   |   |   |   |-- hit
    |   |   |   |   |-- mutants
    |   |   |   |   |-- searching_enemy
    |   |   |   |   |-- threat
    |   |   |   |   |-- tolls
    |   |   |   |   `-- trup
    |   |   |   |-- hail
    |   |   |   |-- help
    |   |   |   |   |-- not_wounded
    |   |   |   |   |-- wounded
    |   |   |   |   |-- wounded_heavy
    |   |   |   |   |   `-- aptechku
    |   |   |   |   |-- wounded_not_see_helper
    |   |   |   |   |-- wounded_psy
    |   |   |   |   |-- wounded_see_helper
    |   |   |   |   `-- wounded_thanx
    |   |   |   |-- multiplayer
    |   |   |   |   |-- team_1
    |   |   |   |   `-- team_2
    |   |   |   |-- music
    |   |   |   |-- reactions
    |   |   |   |   |-- dead_enemy
    |   |   |   |   |-- dead_friend
    |   |   |   |   |-- dead_mutant
    |   |   |   |   |-- dead_neutral
    |   |   |   |   |-- hear_something
    |   |   |   |   |-- joke
    |   |   |   |   |-- music
    |   |   |   |   |-- nothing
    |   |   |   |   |-- see_something
    |   |   |   |   `-- story
    |   |   |   |-- states
    |   |   |   |   |-- breath
    |   |   |   |   |-- fatique
    |   |   |   |   |-- health
    |   |   |   |   |-- idle
    |   |   |   |   |-- meet
    |   |   |   |   |-- panic_human
    |   |   |   |   |-- panic_monster
    |   |   |   |   |-- radiation
    |   |   |   |   |-- sleep
    |   |   |   |   `-- starvation
    |   |   |   |-- talk
    |   |   |   |   |-- abuse
    |   |   |   |   |-- accept
    |   |   |   |   |-- friendly_greeting
    |   |   |   |   |-- intros
    |   |   |   |   |-- jokes
    |   |   |   |   |-- leave
    |   |   |   |   |-- neutral_greeting
    |   |   |   |   |-- raid
    |   |   |   |   |   |-- init
    |   |   |   |   |   `-- reaction
    |   |   |   |   |-- rejection
    |   |   |   |   |-- stories
    |   |   |   |   |-- trade
    |   |   |   |   |   |-- no
    |   |   |   |   |   `-- yes
    |   |   |   |   `-- use
    |   |   |   |-- threat
    |   |   |   |   |-- back_off
    |   |   |   |   |-- drop_weapon
    |   |   |   |   `-- stop
    |   |   |   |-- waiting
    |   |   |   |   `-- moveout
    |   |   |   `-- weather
    |   |   |       |-- bad_weather
    |   |   |       |-- day
    |   |   |       |-- good_weather
    |   |   |       |-- night
    |   |   |       `-- rain
    |   |   |-- freedom
    |   |   |   |-- alife
    |   |   |   |   |-- attack
    |   |   |   |   |-- counter_attack
    |   |   |   |   |-- defence
    |   |   |   |   `-- patrol
    |   |   |   |-- fight
    |   |   |   |   |-- attack
    |   |   |   |   |-- backup
    |   |   |   |   |-- cover_fire
    |   |   |   |   |-- death
    |   |   |   |   |-- detour
    |   |   |   |   |-- enemy
    |   |   |   |   |-- enemy_down
    |   |   |   |   |-- enemy_hit
    |   |   |   |   |-- fire
    |   |   |   |   |-- friend_hitted
    |   |   |   |   |-- friendly_fire
    |   |   |   |   |-- friendly_grenade
    |   |   |   |   |-- grenade
    |   |   |   |   |-- hit
    |   |   |   |   |-- post_combat_wait
    |   |   |   |   |-- searching_enemy
    |   |   |   |   |-- threat
    |   |   |   |   `-- tolls
    |   |   |   |-- hail
    |   |   |   |-- help
    |   |   |   |   |-- combat
    |   |   |   |   |-- not_wounded
    |   |   |   |   |-- wounded
    |   |   |   |   |-- wounded_heavy
    |   |   |   |   |-- wounded_not_see_helper
    |   |   |   |   |-- wounded_psy
    |   |   |   |   |-- wounded_see_helper
    |   |   |   |   `-- wounded_thanx
    |   |   |   |-- music
    |   |   |   |-- reactions
    |   |   |   |   |-- box
    |   |   |   |   |-- joke
    |   |   |   |   |-- music
    |   |   |   |   `-- story
    |   |   |   |-- states
    |   |   |   |   |-- breath
    |   |   |   |   |-- idle
    |   |   |   |   |-- loot
    |   |   |   |   |-- meet
    |   |   |   |   |-- panic_human
    |   |   |   |   |-- panic_monster
    |   |   |   |   |-- sleep
    |   |   |   |   `-- trade
    |   |   |   |-- talk
    |   |   |   |   |-- intros
    |   |   |   |   |-- jokes
    |   |   |   |   `-- use
    |   |   |   `-- threat
    |   |   |       |-- back_off
    |   |   |       `-- drop_weapon
    |   |   |-- killer
    |   |   |   |-- fight
    |   |   |   |   |-- attack
    |   |   |   |   |-- backup
    |   |   |   |   |-- cover_fire
    |   |   |   |   |-- death
    |   |   |   |   |-- detour
    |   |   |   |   |-- enemy
    |   |   |   |   |-- friend_hitted
    |   |   |   |   |-- friendly_fire
    |   |   |   |   |-- friendly_grenade
    |   |   |   |   |-- grenade
    |   |   |   |   |-- hit
    |   |   |   |   |-- searching_enemy
    |   |   |   |   `-- tolls
    |   |   |   |-- hail
    |   |   |   |-- help
    |   |   |   |   |-- not_wounded
    |   |   |   |   |-- wounded
    |   |   |   |   |-- wounded_heavy
    |   |   |   |   |   `-- aptechku
    |   |   |   |   |-- wounded_not_see_helper
    |   |   |   |   |-- wounded_psy
    |   |   |   |   |-- wounded_see_helper
    |   |   |   |   `-- wounded_thanx
    |   |   |   |-- reactions
    |   |   |   |   |-- joke
    |   |   |   |   |-- music
    |   |   |   |   `-- story
    |   |   |   |-- states
    |   |   |   |   |-- breath
    |   |   |   |   |-- idle
    |   |   |   |   |-- loot
    |   |   |   |   |-- meet
    |   |   |   |   |-- panic_human
    |   |   |   |   |-- panic_monster
    |   |   |   |   `-- sleep
    |   |   |   |-- talk
    |   |   |   |   |-- intros
    |   |   |   |   |-- jokes
    |   |   |   |   `-- use
    |   |   |   `-- threat
    |   |   |       |-- back_off
    |   |   |       `-- drop_weapon
    |   |   |-- military
    |   |   |   |-- alife
    |   |   |   |   |-- attack
    |   |   |   |   |-- counter_attack
    |   |   |   |   `-- patrol
    |   |   |   |-- fight
    |   |   |   |   |-- attack
    |   |   |   |   |-- backup
    |   |   |   |   |-- cover_fire
    |   |   |   |   |-- death
    |   |   |   |   |-- detour
    |   |   |   |   |-- enemy
    |   |   |   |   |-- enemy_down
    |   |   |   |   |-- enemy_hit
    |   |   |   |   |-- fire
    |   |   |   |   |-- friend_hitted
    |   |   |   |   |-- friendly_fire
    |   |   |   |   |-- grenade
    |   |   |   |   |-- hit
    |   |   |   |   |-- post_combat_wait
    |   |   |   |   |-- searching_enemy
    |   |   |   |   |-- threat
    |   |   |   |   `-- tolls
    |   |   |   |-- hail
    |   |   |   |-- help
    |   |   |   |   |-- not_wounded
    |   |   |   |   |-- wounded
    |   |   |   |   |-- wounded_heavy
    |   |   |   |   |-- wounded_not_see_helper
    |   |   |   |   |-- wounded_psy
    |   |   |   |   |-- wounded_see_helper
    |   |   |   |   `-- wounded_thanx
    |   |   |   |-- music
    |   |   |   |-- reactions
    |   |   |   |   |-- joke
    |   |   |   |   |-- music
    |   |   |   |   `-- story
    |   |   |   |-- states
    |   |   |   |   |-- breath
    |   |   |   |   |-- idle
    |   |   |   |   |-- loot
    |   |   |   |   |-- meet
    |   |   |   |   |-- panic_human
    |   |   |   |   |-- panic_monster
    |   |   |   |   `-- sleep
    |   |   |   |-- talk
    |   |   |   |   |-- intros
    |   |   |   |   |-- jokes
    |   |   |   |   `-- use
    |   |   |   `-- threat
    |   |   |       |-- back_off
    |   |   |       `-- drop_weapon
    |   |   |-- monolith
    |   |   |   |-- fight
    |   |   |   |   |-- attack
    |   |   |   |   |-- backup
    |   |   |   |   |-- cover_fire
    |   |   |   |   |-- death
    |   |   |   |   |-- detour
    |   |   |   |   |-- enemy
    |   |   |   |   |-- enemy_down
    |   |   |   |   |-- enemy_hit
    |   |   |   |   |-- fire
    |   |   |   |   |-- friend_hitted
    |   |   |   |   |-- friendly_fire
    |   |   |   |   |-- grenade
    |   |   |   |   |-- hit
    |   |   |   |   |-- searching_enemy
    |   |   |   |   |-- threat
    |   |   |   |   `-- tolls
    |   |   |   |-- help
    |   |   |   |   |-- wounded
    |   |   |   |   |-- wounded_heavy
    |   |   |   |   `-- wounded_thanx
    |   |   |   |-- music
    |   |   |   |-- reactions
    |   |   |   |   |-- joke
    |   |   |   |   |-- music
    |   |   |   |   `-- story
    |   |   |   |-- states
    |   |   |   |   |-- breath
    |   |   |   |   |-- idle
    |   |   |   |   |-- loot
    |   |   |   |   |-- meet
    |   |   |   |   |-- panic_human
    |   |   |   |   |-- panic_monster
    |   |   |   |   `-- sleep
    |   |   |   |-- talk
    |   |   |   |   |-- intros
    |   |   |   |   |-- jokes
    |   |   |   |   `-- use
    |   |   |   `-- threat
    |   |   |       |-- back_off
    |   |   |       `-- drop_weapon
    |   |   |-- stalker
    |   |   |   |-- alife
    |   |   |   |   |-- attack
    |   |   |   |   |-- counter_attack
    |   |   |   |   |-- defence
    |   |   |   |   |-- patrol
    |   |   |   |   `-- sos
    |   |   |   |-- fight
    |   |   |   |   |-- attack
    |   |   |   |   |-- backup
    |   |   |   |   |-- cover_fire
    |   |   |   |   |-- death
    |   |   |   |   |-- detour
    |   |   |   |   |-- enemy
    |   |   |   |   |-- enemy_down
    |   |   |   |   |-- enemy_hit
    |   |   |   |   |-- fire
    |   |   |   |   |-- friend_hitted
    |   |   |   |   |-- friendly_fire
    |   |   |   |   |-- friendly_grenade
    |   |   |   |   |-- grenade
    |   |   |   |   |-- hit
    |   |   |   |   |-- post_combat_wait
    |   |   |   |   |-- searching_enemy
    |   |   |   |   |-- threat
    |   |   |   |   `-- tolls
    |   |   |   |-- help
    |   |   |   |   |-- combat
    |   |   |   |   |-- wounded
    |   |   |   |   |-- wounded_heavy
    |   |   |   |   `-- wounded_thanx
    |   |   |   |-- music
    |   |   |   |-- reactions
    |   |   |   |   |-- box
    |   |   |   |   |-- joke
    |   |   |   |   |-- music
    |   |   |   |   |-- s_story
    |   |   |   |   `-- story
    |   |   |   |-- states
    |   |   |   |   |-- breath
    |   |   |   |   |-- idle
    |   |   |   |   |-- loot
    |   |   |   |   |-- meet
    |   |   |   |   |-- panic_human
    |   |   |   |   |-- panic_monster
    |   |   |   |   |-- s_story
    |   |   |   |   |-- sleep
    |   |   |   |   `-- trade
    |   |   |   |-- talk
    |   |   |   |   |-- intros
    |   |   |   |   |-- jokes
    |   |   |   |   `-- use
    |   |   |   `-- threat
    |   |   |       |-- back_off
    |   |   |       `-- drop_weapon
    |   |   `-- zombied
    |   |       |-- fight
    |   |       |   |-- attack
    |   |       |   |-- death
    |   |       |   |-- enemy
    |   |       |   `-- hit
    |   |       `-- states
    |   |           |-- idle
    |   |           `-- rising
    |   |-- human_02
    |   |   |-- bandit
    |   |   |   |-- alife
    |   |   |   |   |-- attack
    |   |   |   |   |-- counter_attack
    |   |   |   |   |-- defence
    |   |   |   |   `-- patrol
    |   |   |   |-- fight
    |   |   |   |   |-- attack
    |   |   |   |   |-- backup
    |   |   |   |   |-- cover_fire
    |   |   |   |   |-- danger_sound
    |   |   |   |   |-- death
    |   |   |   |   |-- detour
    |   |   |   |   |-- enemy
    |   |   |   |   |-- friend_hitted
    |   |   |   |   |-- friendly_fire
    |   |   |   |   |-- friendly_grenade
    |   |   |   |   |-- grenade
    |   |   |   |   |-- hit
    |   |   |   |   |-- post_combat_wait
    |   |   |   |   |-- searching_enemy
    |   |   |   |   `-- tolls
    |   |   |   |-- hail
    |   |   |   |-- help
    |   |   |   |   |-- not_wounded
    |   |   |   |   |-- wounded
    |   |   |   |   |-- wounded_heavy
    |   |   |   |   |-- wounded_not_see_helper
    |   |   |   |   |-- wounded_psy
    |   |   |   |   |-- wounded_see_helper
    |   |   |   |   `-- wounded_thanx
    |   |   |   |-- music
    |   |   |   |-- reactions
    |   |   |   |   |-- joke
    |   |   |   |   |-- music
    |   |   |   |   `-- story
    |   |   |   |-- states
    |   |   |   |   |-- breath
    |   |   |   |   |-- idle
    |   |   |   |   |-- loot
    |   |   |   |   |-- meet
    |   |   |   |   |-- panic_human
    |   |   |   |   |-- panic_monster
    |   |   |   |   `-- sleep
    |   |   |   |-- talk
    |   |   |   |   |-- intros
    |   |   |   |   |-- jokes
    |   |   |   |   `-- use
    |   |   |   `-- threat
    |   |   |       |-- back_off
    |   |   |       `-- drop_weapon
    |   |   |-- csky
    |   |   |   |-- alife
    |   |   |   |   |-- attack
    |   |   |   |   |-- counter_attack
    |   |   |   |   |-- defence
    |   |   |   |   `-- patrol
    |   |   |   |-- fight
    |   |   |   |   |-- attack
    |   |   |   |   |-- backup
    |   |   |   |   |-- cover_fire
    |   |   |   |   |-- death
    |   |   |   |   |-- detour
    |   |   |   |   |-- enemy
    |   |   |   |   |-- enemy_down
    |   |   |   |   |-- enemy_hit
    |   |   |   |   |-- fire
    |   |   |   |   |-- friend_hitted
    |   |   |   |   |-- friendly_fire
    |   |   |   |   |-- grenade
    |   |   |   |   |-- hit
    |   |   |   |   |-- post_combat_wait
    |   |   |   |   |-- searching_enemy
    |   |   |   |   |-- threat
    |   |   |   |   `-- tolls
    |   |   |   |-- help
    |   |   |   |   |-- wounded
    |   |   |   |   |-- wounded_heavy
    |   |   |   |   `-- wounded_thanx
    |   |   |   |-- music
    |   |   |   |-- reactions
    |   |   |   |   |-- box
    |   |   |   |   |-- joke
    |   |   |   |   |-- music
    |   |   |   |   `-- story
    |   |   |   |-- states
    |   |   |   |   |-- breath
    |   |   |   |   |-- idle
    |   |   |   |   |-- loot
    |   |   |   |   |-- meet
    |   |   |   |   |-- panic_human
    |   |   |   |   |-- panic_monster
    |   |   |   |   `-- sleep
    |   |   |   |-- talk
    |   |   |   |   |-- intros
    |   |   |   |   |-- jokes
    |   |   |   |   `-- use
    |   |   |   `-- threat
    |   |   |       |-- back_off
    |   |   |       `-- drop_weapon
    |   |   |-- dolg
    |   |   |   |-- alife
    |   |   |   |   |-- attack
    |   |   |   |   |-- counter_attack
    |   |   |   |   |-- defence
    |   |   |   |   `-- patrol
    |   |   |   |-- fight
    |   |   |   |   |-- attack
    |   |   |   |   |-- backup
    |   |   |   |   |-- cover_fire
    |   |   |   |   |-- death
    |   |   |   |   |-- detour
    |   |   |   |   |-- enemy
    |   |   |   |   |-- enemy_down
    |   |   |   |   |-- enemy_hit
    |   |   |   |   |-- fire
    |   |   |   |   |-- friend_hitted
    |   |   |   |   |-- friendly_fire
    |   |   |   |   |-- friendly_grenade
    |   |   |   |   |-- grenade
    |   |   |   |   |-- hit
    |   |   |   |   |-- post_combat_wait
    |   |   |   |   |-- searching_enemy
    |   |   |   |   |-- threat
    |   |   |   |   `-- tolls
    |   |   |   |-- hail
    |   |   |   |-- help
    |   |   |   |   |-- combat
    |   |   |   |   |-- not_wounded
    |   |   |   |   |-- wounded
    |   |   |   |   |-- wounded_heavy
    |   |   |   |   |-- wounded_not_see_helper
    |   |   |   |   |-- wounded_psy
    |   |   |   |   |-- wounded_see_helper
    |   |   |   |   `-- wounded_thanx
    |   |   |   |-- music
    |   |   |   |-- reactions
    |   |   |   |   |-- box
    |   |   |   |   |-- joke
    |   |   |   |   |-- music
    |   |   |   |   `-- story
    |   |   |   |-- states
    |   |   |   |   |-- breath
    |   |   |   |   |-- idle
    |   |   |   |   |-- loot
    |   |   |   |   |-- meet
    |   |   |   |   |-- panic_human
    |   |   |   |   |-- panic_monster
    |   |   |   |   |-- sleep
    |   |   |   |   `-- trade
    |   |   |   |-- talk
    |   |   |   |   |-- intros
    |   |   |   |   |-- jokes
    |   |   |   |   `-- use
    |   |   |   `-- threat
    |   |   |       |-- back_off
    |   |   |       `-- drop_weapon
    |   |   |-- ecolog
    |   |   |   |-- fight
    |   |   |   |   |-- attack
    |   |   |   |   |-- backup
    |   |   |   |   |-- cover_fire
    |   |   |   |   |-- danger_sound
    |   |   |   |   |-- death
    |   |   |   |   |-- detour
    |   |   |   |   |-- enemy
    |   |   |   |   |-- enemy_down
    |   |   |   |   |-- enemy_hit
    |   |   |   |   |-- fire
    |   |   |   |   |-- friend_hitted
    |   |   |   |   |-- friendly_fire
    |   |   |   |   |-- friendly_grenade
    |   |   |   |   |-- grenade
    |   |   |   |   |-- hit
    |   |   |   |   |-- mutants
    |   |   |   |   |-- searching_enemy
    |   |   |   |   |-- threat
    |   |   |   |   |-- tolls
    |   |   |   |   `-- trup
    |   |   |   |-- hail
    |   |   |   |-- help
    |   |   |   |   |-- not_wounded
    |   |   |   |   |-- wounded
    |   |   |   |   |-- wounded_heavy
    |   |   |   |   |   `-- aptechku
    |   |   |   |   |-- wounded_not_see_helper
    |   |   |   |   |-- wounded_psy
    |   |   |   |   |-- wounded_see_helper
    |   |   |   |   `-- wounded_thanx
    |   |   |   |-- multiplayer
    |   |   |   |   |-- team_1
    |   |   |   |   `-- team_2
    |   |   |   |-- music
    |   |   |   |-- reactions
    |   |   |   |   |-- dead_enemy
    |   |   |   |   |-- dead_friend
    |   |   |   |   |-- dead_mutant
    |   |   |   |   |-- dead_neutral
    |   |   |   |   |-- hear_something
    |   |   |   |   |-- joke
    |   |   |   |   |-- music
    |   |   |   |   |-- nothing
    |   |   |   |   |-- see_something
    |   |   |   |   `-- story
    |   |   |   |-- states
    |   |   |   |   |-- breath
    |   |   |   |   |-- fatique
    |   |   |   |   |-- health
    |   |   |   |   |-- idle
    |   |   |   |   |-- meet
    |   |   |   |   |-- panic_human
    |   |   |   |   |-- panic_monster
    |   |   |   |   |-- radiation
    |   |   |   |   |-- sleep
    |   |   |   |   `-- starvation
    |   |   |   |-- talk
    |   |   |   |   |-- abuse
    |   |   |   |   |-- accept
    |   |   |   |   |-- friendly_greeting
    |   |   |   |   |-- intros
    |   |   |   |   |-- jokes
    |   |   |   |   |-- leave
    |   |   |   |   |-- neutral_greeting
    |   |   |   |   |-- raid
    |   |   |   |   |   |-- init
    |   |   |   |   |   `-- reaction
    |   |   |   |   |-- rejection
    |   |   |   |   |-- stories
    |   |   |   |   |-- trade
    |   |   |   |   |   |-- no
    |   |   |   |   |   `-- yes
    |   |   |   |   `-- use
    |   |   |   |-- threat
    |   |   |   |   |-- back_off
    |   |   |   |   |-- drop_weapon
    |   |   |   |   `-- stop
    |   |   |   |-- waiting
    |   |   |   |   `-- moveout
    |   |   |   `-- weather
    |   |   |       |-- bad_weather
    |   |   |       |-- day
    |   |   |       |-- good_weather
    |   |   |       |-- night
    |   |   |       `-- rain
    |   |   |-- freedom
```
