```bash
mkdir dota && 
curl -O http://hex6.se/dota/hero_sounds.txt -O http://hex6.se/dota/game_sounds_creeps.txt -O http://hex6.se/dota/game_sounds_items.tx -O http://hex6.se/dota/game_sounds_music.txt -O http://hex6.se/dota/item_icons.txt -O http://hex6.se/dota/ability_names.txt -O http://hex6.se/dota/modifiers.txt -O http://hex6.se/dota/modifier_functions.txt -O http://hex6.se/dota/hero_model_names.txt -O http://hex6.se/dota/creep_model_names.txt -O http://hex6.se/dota/prop_model_names.txt -O http://hex6.se/dota/projectile_model_names.txt -O http://hex6.se/dota/courier_model_names.txt -O http://hex6.se/dota/cosmetic_item_model_names.txt -O http://hex6.se/dota/building_model_names.txt -O http://hex6.se/dota/npc_abilities_override.txt -O http://hex6.se/dota/addon_name_shops.txt
&& mkdir dota/particles && cd dota/particles &&
curl -O http://hex6.se/dota/particles/particles_abaddon.txt -O http://hex6.se/dota/particles/particles_alchemist.txt -O http://hex6.se/dota/particles/particles_ancient_apparition.txt -O http://hex6.se/dota/particles/particles_antimage.txt -O http://hex6.se/dota/particles/particles_axe.txt -O http://hex6.se/dota/particles/particles/particles_bane.txt -O http://hex6.se/dota/particles/particles_batrider.txt -O http://hex6.se/dota/particles/particles_beastmaster.txt -O http://hex6.se/dota/particles/particles_bloodseeker.txt -O http://hex6.se/dota/particles/particles_bounty_hunter.txt -O http://hex6.se/dota/particles/particles_brewmaster.txt -O http://hex6.se/dota/particles/particles_bringer.txt -O http://hex6.se/dota/particles/particles_bristleback.txt -O http://hex6.se/dota/particles/particles_broodmother.txt -O http://hex6.se/dota/particles/particles_centaur.txt -O http://hex6.se/dota/particles/particles_chaos_knight.txt -O http://hex6.se/dota/particles/particles_chen.txt -O http://hex6.se/dota/particles/particles_clinkz.txt -O http://hex6.se/dota/particles/particles_crystalmaiden.txt -O http://hex6.se/dota/particles/particles_dark_seer.txt -O http://hex6.se/dota/particles/particles_dazzle.txt -O http://hex6.se/dota/particles/particles_death_prophet.txt -O http://hex6.se/dota/particles/particles_disruptor.txt -O http://hex6.se/dota/particles/particles_doom_bringer.txt -O http://hex6.se/dota/particles/particles_dragon_knight.txt -O http://hex6.se/dota/particles/particles_drow.txt -O http://hex6.se/dota/particles/particles_earthshaker.txt -O http://hex6.se/dota/particles/particles_earth_spirit.txt -O http://hex6.se/dota/particles/particles_elder_titan.txt -O http://hex6.se/dota/particles/particles_ember_spirit.txt -O http://hex6.se/dota/particles/particles_enchantress.txt -O http://hex6.se/dota/particles/particles_enigma.txt -O http://hex6.se/dota/particles/particles_faceless_void.txt -O http://hex6.se/dota/particles/particles_furion.txt -O http://hex6.se/dota/particles/particles_gyrocopter.txt -O http://hex6.se/dota/particles/particles_huskar.txt -O http://hex6.se/dota/particles/particles_invoker.txt -O http://hex6.se/dota/particles/particles_jakiro.txt -O http://hex6.se/dota/particles/particles_juggernaut.txt -O http://hex6.se/dota/particles/particles_keeper_of_the_light.txt -O http://hex6.se/dota/particles/particles_knight.txt -O http://hex6.se/dota/particles/particles_kun.txt -O http://hex6.se/dota/particles/particles_legion_commander.txt -O http://hex6.se/dota/particles/particles_leoric.txt -O http://hex6.se/dota/particles/particles_leshrac.txt -O http://hex6.se/dota/particles/particles_lich.txt -O http://hex6.se/dota/particles/particles_life_stealer.txt -O http://hex6.se/dota/particles/particles_lina.txt -O http://hex6.se/dota/particles/particles_lion.txt -O http://hex6.se/dota/particles/particles_lone_druid.txt -O http://hex6.se/dota/particles/particles_luna.txt -O http://hex6.se/dota/particles/particles_lycan.txt -O http://hex6.se/dota/particles/particles_magnataur.txt -O http://hex6.se/dota/particles/particles_medusa.txt -O http://hex6.se/dota/particles/particles_meepo.txt -O http://hex6.se/dota/particles/particles_mirana.txt -O http://hex6.se/dota/particles/particles_morphling.txt -O http://hex6.se/dota/particles/particles_necrolyte.txt -O http://hex6.se/dota/particles/particles_nevermore.txt -O http://hex6.se/dota/particles/particles_night_stalker.txt -O http://hex6.se/dota/particles/particles_nyx_assassin.txt -O http://hex6.se/dota/particles/particles_obsidian_destroyer.txt -O http://hex6.se/dota/particles/particles_ogre_magi.txt -O http://hex6.se/dota/particles/particles_omniknight.txt -O http://hex6.se/dota/particles/particles_phantom_assassin.txt -O http://hex6.se/dota/particles/particles_phantom_lancer.txt -O http://hex6.se/dota/particles/particles_phoenix.txt -O http://hex6.se/dota/particles/particles_prophet.txt -O http://hex6.se/dota/particles/particles_puck.txt -O http://hex6.se/dota/particles/particles_pudge.txt -O http://hex6.se/dota/particles/particles_pugna.txt -O http://hex6.se/dota/particles/particles_queenofpain.txt -O http://hex6.se/dota/particles/particles_rattletrap.txt -O http://hex6.se/dota/particles/particles_razor.txt -O http://hex6.se/dota/particles/particles_rhasta.txt -O http://hex6.se/dota/particles/particles_riki.txt -O http://hex6.se/dota/particles/particles_rubick.txt -O http://hex6.se/dota/particles/particles_sandking.txt -O http://hex6.se/dota/particles/particles_shadowshaman.txt -O http://hex6.se/dota/particles/particles_shadow_demon.txt -O http://hex6.se/dota/particles/particles_shredder.txt -O http://hex6.se/dota/particles/particles_silencer.txt -O http://hex6.se/dota/particles/particles_siren.txt -O http://hex6.se/dota/particles/particles_skeletonking.txt -O http://hex6.se/dota/particles/particles_skywrath_mage.txt -O http://hex6.se/dota/particles/particles_slardar.txt -O http://hex6.se/dota/particles/particles_slark.txt -O http://hex6.se/dota/particles/particles_sniper.txt -O http://hex6.se/dota/particles/particles_spectre.txt -O http://hex6.se/dota/particles/particles_spirit_breaker.txt -O http://hex6.se/dota/particles/particles_stormspirit.txt -O http://hex6.se/dota/particles/particles_sven.txt -O http://hex6.se/dota/particles/particles_templar_assassin.txt -O http://hex6.se/dota/particles/particles_terrorblade.txt -O http://hex6.se/dota/particles/particles_tidehunter.txt -O http://hex6.se/dota/particles/particles_tinker.txt -O http://hex6.se/dota/particles/particles_tiny.txt -O http://hex6.se/dota/particles/particles_titan.txt -O http://hex6.se/dota/particles/particles_treant.txt -O http://hex6.se/dota/particles/particles_troll_warlord.txt -O http://hex6.se/dota/particles/particles_tusk.txt -O http://hex6.se/dota/particles/particles_undying.txt -O http://hex6.se/dota/particles/particles_ursa.txt -O http://hex6.se/dota/particles/particles_vengeful.txt -O http://hex6.se/dota/particles/particles_venomancer.txt -O http://hex6.se/dota/particles/particles_viper.txt -O http://hex6.se/dota/particles/particles_visage.txt -O http://hex6.se/dota/particles/particles_void.txt -O http://hex6.se/dota/particles/particles_warlock.txt -O http://hex6.se/dota/particles/particles_weaver.txt -O http://hex6.se/dota/particles/particles_windrunner.txt -O http://hex6.se/dota/particles/particles_wisp.txt -O http://hex6.se/dota/particles/particles_witchdoctor.txt -O http://hex6.se/dota/particles/particles_zuus.txt
```
