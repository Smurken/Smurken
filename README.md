### Hi there 👋

<!--
**Smurken/Smurken** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->### Hi there 👋

<!--
**Smurken/Smurken** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->---- Minecraft Crash Report ----

WARNING: coremods are present:
  IELoadingPlugin (ImmersiveEngineering-core-0.12-98.jar)
  MekanismCoremod (Mekanism-1.12.2-9.8.3.390.jar)
  ItemPatchingLoader (ItemPhysic_Full_1.4.37_mc1.12.2.jar)
  TransformerLoader (OpenComputers-MC1.12.2-1.7.7+5413028.jar)
  MicdoodlePlugin (MicdoodleCore-1.12.2-4.0.2.280.jar)
  PhosphorFMLLoadingPlugin (phosphor-forge-mc1.12.2-0.2.7-universal.jar)
  Quark Plugin (Quark-r1.6-179.jar)
  AppleCore (AppleCore-mc1.12.2-3.4.0.jar)
  BiomeTweakerCore (BiomeTweakerCore-1.12.2-1.0.39.jar)
  UniDictCoreMod (UniDict-1.12.2-3.0.10.jar)
  EnderCorePlugin (EnderCore-1.12.2-0.5.76-core.jar)
  LoadingPlugin (ResourceLoader-MC1.12.1-1.5.3.jar)
  CoreMod (Aroma1997Core-1.12.2-2.0.0.2.b167.jar)
  Inventory Tweaks Coremod (InventoryTweaks-1.64+dev.151.jar)
  LoadingPlugin (RandomThings-MC1.12.2-4.2.7.4.jar)
  RandomPatches (randompatches-1.12.2-1.22.1.10.jar)
  Do not report to Forge! (If you haven't disabled the FoamFix coremod, try disabling it in the config! Note that this bit of text will still appear.) (foamfix-0.10.15-1.12.2.jar)
  ForgelinPlugin (Forgelin-1.8.4.jar)
  CreativePatchingLoader (CreativeCore_v1.10.70_mc1.12.2.jar)
  OpenModsCorePlugin (OpenModsLib-1.12.2-0.12.2.jar)
  Ar_CorePlugin (additionalresources-1.9.4-0.2.0.28+47cd0bd_signed.jar)
  ApotheosisCore (Apotheosis-1.12.2-1.12.5.jar)
  CTMCorePlugin (CTM-MC1.12.2-1.0.2.31.jar)
  Plugin (NotEnoughIDs-1.5.4.4.jar)
  AstralCore (astralsorcery-1.12.2-1.10.27.jar)
  HCASM (HammerLib-1.12.2-2.0.6.32.jar)
Contact their authors BEFORE contacting forge

// My bad.

Time: 12/23/22 4:43 AM
Description: Rendering screen

java.lang.IndexOutOfBoundsException: Index: 0, Size: 0
	at java.util.ArrayList.rangeCheck(ArrayList.java:653)
	at java.util.ArrayList.get(ArrayList.java:429)
	at java.util.Collections$SynchronizedList.get(Collections.java:2417)
	at appeng.client.me.ItemRepo.getReferenceItem(ItemRepo.java:74)
	at appeng.client.me.InternalSlotME.getAEStack(InternalSlotME.java:45)
	at appeng.client.me.InternalSlotME.getStack(InternalSlotME.java:41)
	at appeng.client.me.SlotME.func_75211_c(SlotME.java:53)
	at me.desht.pneumaticcraft.client.ClientEventHandler.drawCustomDurabilityBars(ClientEventHandler.java:598)
	at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_2995_ClientEventHandler_drawCustomDurabilityBars_Pre.invoke(.dynamic)
	at net.minecraftforge.fml.common.eventhandler.ASMEventHandler.invoke(ASMEventHandler.java:90)
	at net.minecraftforge.fml.common.eventhandler.EventBus.post(EventBus.java:182)
	at net.minecraftforge.client.ForgeHooksClient.drawScreen(ForgeHooksClient.java:395)
	at net.minecraft.client.renderer.EntityRenderer.func_181560_a(EntityRenderer.java:1124)
	at net.minecraft.client.Minecraft.func_71411_J(Minecraft.java:1119)
	at net.minecraft.client.Minecraft.func_99999_d(Minecraft.java:398)
	at net.minecraft.client.main.Main.main(SourceFile:123)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:497)
	at net.minecraft.launchwrapper.Launch.launch(Launch.java:135)
	at net.minecraft.launchwrapper.Launch.main(Launch.java:28)


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Client thread
Stacktrace:
	at java.util.ArrayList.rangeCheck(ArrayList.java:653)
	at java.util.ArrayList.get(ArrayList.java:429)
	at java.util.Collections$SynchronizedList.get(Collections.java:2417)
	at appeng.client.me.ItemRepo.getReferenceItem(ItemRepo.java:74)
	at appeng.client.me.InternalSlotME.getAEStack(InternalSlotME.java:45)
	at appeng.client.me.InternalSlotME.getStack(InternalSlotME.java:41)
	at appeng.client.me.SlotME.func_75211_c(SlotME.java:53)
	at me.desht.pneumaticcraft.client.ClientEventHandler.drawCustomDurabilityBars(ClientEventHandler.java:598)
	at net.minecraftforge.fml.common.eventhandler.ASMEventHandler_2995_ClientEventHandler_drawCustomDurabilityBars_Pre.invoke(.dynamic)
	at net.minecraftforge.fml.common.eventhandler.ASMEventHandler.invoke(ASMEventHandler.java:90)
	at net.minecraftforge.fml.common.eventhandler.EventBus.post(EventBus.java:182)
	at net.minecraftforge.client.ForgeHooksClient.drawScreen(ForgeHooksClient.java:395)

-- Screen render details --
Details:
	Screen name: appeng.client.gui.implementations.GuiCraftingTerm
	Mouse location: Scaled: (483, 133). Absolute: (966, 812)
	Screen size: Scaled: (960, 540). Absolute: (1920, 1080). Scale factor of 2

-- Affected level --
Details:
	Level name: MpServer
	All players: 1 total; [GCEntityClientPlayerMP['agnetha_kastrull'/430, l='MpServer', x=-252.47, y=86.63, z=2687.03]]
	Chunk stats: MultiplayerChunkCache: 49, 49
	Level seed: 0
	Level generator: ID 06 - botania-skyblock, ver 0. Features enabled: false
	Level generator options: 
	Level spawn location: World: (-217,86,2653), Chunk: (at 7,5,13 in -14,165; contains blocks -224,0,2640 to -209,255,2655), Region: (-1,5; contains chunks -32,160 to -1,191, blocks -512,0,2560 to -1,255,3071)
	Level time: 3886135 game time, 4304565 day time
	Level dimension: 0
	Level storage version: 0x00000 - Unknown?
	Level weather: Rain time: 0 (now: false), thunder time: 0 (now: false)
	Level game mode: Game mode: survival (ID 0). Hardcore: false. Cheats: false
	Forced entities: 22 total; [EntityCrystal['item.item.itemrockcrystalsimple'/384, l='MpServer', x=-251.40, y=86.00, z=2699.25], EntityCrystal['item.item.itemrockcrystalsimple'/385, l='MpServer', x=-251.35, y=86.00, z=2699.28], EntityCrystal['item.item.itemrockcrystalsimple'/386, l='MpServer', x=-252.47, y=86.00, z=2699.82], EntityItem['item.tile.torch'/3739, l='MpServer', x=-254.88, y=86.00, z=2685.88], EntitySkeleton['Skeleton'/2909, l='MpServer', x=-256.50, y=2.88, z=2685.50], EntityItem['item.item.seeds_pumpkin'/1572, l='MpServer', x=-259.45, y=86.00, z=2681.15], EntityItem['item.item.karatgarden:seed_carrot_base'/1832, l='MpServer', x=-258.03, y=86.00, z=2679.50], EntityItem['item.item.egg'/365, l='MpServer', x=-261.97, y=86.00, z=2696.09], EntityItem['item.item.egg'/366, l='MpServer', x=-257.47, y=86.00, z=2701.91], GCEntityClientPlayerMP['agnetha_kastrull'/430, l='MpServer', x=-252.47, y=86.63, z=2687.03], EntityChicken['Chicken'/367, l='MpServer', x=-261.17, y=86.00, z=2696.64], EntityChicken['Chicken'/372, l='MpServer', x=-264.49, y=86.00, z=2699.81], EntityCrystal['item.item.itemrockcrystalsimple'/373, l='MpServer', x=-247.63, y=86.00, z=2687.64], EntityCrystal['item.item.itemrockcrystalsimple'/374, l='MpServer', x=-247.49, y=86.00, z=2687.99], EntityCrystal['item.item.itemrockcrystalsimple'/375, l='MpServer', x=-247.38, y=86.00, z=2687.82], EntityItem['item.item.karatgarden:seed_carrot_base'/1591, l='MpServer', x=-259.60, y=86.00, z=2680.74], EntityZombie['Zombie'/378, l='MpServer', x=-250.70, y=81.00, z=2696.30], EntityCrystal['item.item.itemrockcrystalsimple'/379, l='MpServer', x=-247.15, y=86.00, z=2688.07], EntityCrystal['item.item.itemrockcrystalsimple'/380, l='MpServer', x=-251.49, y=86.00, z=2699.19], EntityCrystal['item.item.itemrockcrystalsimple'/381, l='MpServer', x=-251.52, y=86.00, z=2699.06], EntityCrystal['item.item.itemrockcrystalsimple'/382, l='MpServer', x=-251.56, y=86.00, z=2698.84], EntityCrystal['item.item.itemrockcrystalsimple'/383, l='MpServer', x=-251.77, y=86.00, z=2699.48]]
	Retry entities: 0 total; []
	Server brand: fml,forge
	Server type: Integrated singleplayer server
Stacktrace:
	at net.minecraft.client.multiplayer.WorldClient.func_72914_a(WorldClient.java:420)
	at net.minecraft.client.Minecraft.func_71396_d(Minecraft.java:2741)
	at net.minecraft.client.Minecraft.func_99999_d(Minecraft.java:419)
	at net.minecraft.client.main.Main.main(SourceFile:123)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:497)
	at net.minecraft.launchwrapper.Launch.launch(Launch.java:135)
	at net.minecraft.launchwrapper.Launch.main(Launch.java:28)

-- System Details --
Details:
	Minecraft Version: 1.12.2
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 1.8.0_51, Oracle Corporation
	Java VM Version: Java HotSpot(TM) 64-Bit Server VM (mixed mode), Oracle Corporation
	Memory: 2186104104 bytes (2084 MB) / 6861357056 bytes (6543 MB) up to 15003025408 bytes (14308 MB)
	JVM Flags: 3 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xmx16096m -Xms256m
	IntCache: cache: 0, tcache: 0, allocated: 0, tallocated: 0
	FML: MCP 9.42 Powered by Forge 14.23.5.2860 292 mods loaded, 292 mods active
	States: 'U' = Unloaded 'L' = Loaded 'C' = Constructed 'H' = Pre-initialized 'I' = Initialized 'J' = Post-initialized 'A' = Available 'D' = Disabled 'E' = Errored

	| State  | ID                                | Version                            | Source                                                     | Signature                                |
	|:------ |:--------------------------------- |:---------------------------------- |:---------------------------------------------------------- |:---------------------------------------- |
	| LCHIJA | minecraft                         | 1.12.2                             | minecraft.jar                                              | None                                     |
	| LCHIJA | mcp                               | 9.42                               | minecraft.jar                                              | None                                     |
	| LCHIJA | FML                               | 8.0.99.99                          | forge-1.12.2-14.23.5.2860.jar                              | e3c3d50c7c986df74c645c0ac54639741c90a557 |
	| LCHIJA | forge                             | 14.23.5.2860                       | forge-1.12.2-14.23.5.2860.jar                              | e3c3d50c7c986df74c645c0ac54639741c90a557 |
	| LCHIJA | additionalresources               | 0.1.1                              | additionalresources-1.9.4-0.2.0.28+47cd0bd_signed.jar      | None                                     |
	| LCHIJA | creativecoredummy                 | 1.0.0                              | minecraft.jar                                              | None                                     |
	| LCHIJA | itemphysic                        | 1.4.0                              | minecraft.jar                                              | None                                     |
	| LCHIJA | micdoodlecore                     |                                    | minecraft.jar                                              | None                                     |
	| LCHIJA | openmodscore                      | 0.12.2                             | minecraft.jar                                              | None                                     |
	| LCHIJA | biometweakercore                  | 1.0.39                             | minecraft.jar                                              | None                                     |
	| LCHIJA | foamfixcore                       | 7.7.4                              | minecraft.jar                                              | None                                     |
	| LCHIJA | opencomputers|core                | 1.7.7+5413028                      | minecraft.jar                                              | None                                     |
	| LCHIJA | randompatches                     | 1.12.2-1.22.1.10                   | randompatches-1.12.2-1.22.1.10.jar                         | None                                     |
	| LCHIJA | tweakersconstruct                 | 1.12.2-1.6.1                       | tweakersconstruct-1.12.2-1.6.1.jar                         | None                                     |
	| LCHIJA | crafttweaker                      | 4.1.20                             | CraftTweaker2-1.12-4.1.20.680.jar                          | None                                     |
	| LCHIJA | endertweaker                      | 1.2.0                              | EnderTweaker-1.12.2-1.2.0.jar                              | None                                     |
	| LCHIJA | mtlib                             | 3.0.7                              | MTLib-3.0.7.jar                                            | None                                     |
	| LCHIJA | modtweaker                        | 4.0.19                             | modtweaker-4.0.20.11.jar                                   | None                                     |
	| LCHIJA | jei                               | 4.16.1.302                         | jei_1.12.2-4.16.1.302.jar                                  | None                                     |
	| LCHIJA | abyssalcraft                      | 1.10.4                             | AbyssalCraft-1.12.2-1.10.4.jar                             | 220f10d3a93b3ff5fbaa7434cc629d863d6751b9 |
	| LCHIJA | ctm                               | MC1.12.2-1.0.2.31                  | CTM-MC1.12.2-1.0.2.31.jar                                  | None                                     |
	| LCHIJA | chisel                            | MC1.12.2-1.0.2.45                  | Chisel-MC1.12.2-1.0.2.45.jar                               | None                                     |
	| LCHIJA | baubles                           | 1.5.2                              | Baubles-1.12-1.5.2.jar                                     | None                                     |
	| LCHIJA | endercore                         | 1.12.2-0.5.76                      | EnderCore-1.12.2-0.5.76.jar                                | None                                     |
	| LCHIJA | codechickenlib                    | 3.2.3.358                          | CodeChickenLib-1.12.2-3.2.3.358-universal.jar              | f1850c39b2516232a2108a7bd84d1cb5df93b261 |
	| LCHIJA | redstoneflux                      | 2.1.1                              | RedstoneFlux-1.12-2.1.1.1-universal.jar                    | None                                     |
	| LCHIJA | cofhcore                          | 4.6.6                              | CoFHCore-1.12.2-4.6.6.1-universal.jar                      | None                                     |
	| LCHIJA | brandonscore                      | 2.4.20                             | BrandonsCore-1.12.2-2.4.20.162-universal.jar               | None                                     |
	| LCHIJA | cofhworld                         | 1.4.0                              | CoFHWorld-1.12.2-1.4.0.1-universal.jar                     | None                                     |
	| LCHIJA | thermalfoundation                 | 2.6.7                              | ThermalFoundation-1.12.2-2.6.7.1-universal.jar             | None                                     |
	| LCHIJA | draconicevolution                 | 2.3.28                             | Draconic-Evolution-1.12.2-2.3.28.354-universal.jar         | None                                     |
	| LCHIJA | thermalexpansion                  | 5.5.7                              | ThermalExpansion-1.12.2-5.5.7.1-universal.jar              | None                                     |
	| LCHIJA | tombstone                         | 4.5.7                              | tombstone-4.5.7-1.12.2.jar                                 | None                                     |
	| LCHIJA | enderio                           | 5.2.59                             | EnderIO-1.12.2-5.2.59.jar                                  | None                                     |
	| LCHIJA | enderiointegrationtic             | 5.2.59                             | EnderIO-1.12.2-5.2.59.jar                                  | None                                     |
	| LCHIJA | mantle                            | 1.12-1.3.3.55                      | Mantle-1.12-1.3.3.55.jar                                   | None                                     |
	| LCHIJA | materialispreload                 | 1.2.5                              | materialis-1.12.2-1.2.5.jar                                | None                                     |
	| LCHIJA | quark                             | r1.6-179                           | Quark-r1.6-179.jar                                         | None                                     |
	| LCHIJA | tinkers_reforged_preload          | 1.5.6                              | tinkers_reforged-1.5.6.jar                                 | None                                     |
	| LCHIJA | twilightforest                    | 3.11.1021                          | twilightforest-1.12.2-3.11.1021-universal.jar              | None                                     |
	| LCHIJA | tconstruct                        | 1.12.2-2.13.0.183                  | TConstruct-1.12.2-2.13.0.183.jar                           | None                                     |
	| LCHIJA | acintegration                     | 1.11.3                             | AbyssalCraft Integration-1.12.2-1.11.3.jar                 | 220f10d3a93b3ff5fbaa7434cc629d863d6751b9 |
	| LCHIJA | fastbench                         | 1.7.3                              | FastWorkbench-1.12.2-1.7.3.jar                             | None                                     |
	| LCHIJA | actuallyadditions                 | 1.12.2-r152                        | ActuallyAdditions-1.12.2-r152.jar                          | None                                     |
	| LCHIJA | appliedenergistics2               | rv6-stable-7-extended_life-v0.53.8 | appliedenergistics2-rv6-stable-7-extended_life-v0.53.8.jar | None                                     |
	| LCHIJA | bdlib                             | 1.14.3.12                          | bdlib-1.14.3.12-mc1.12.2.jar                               | None                                     |
	| LCHIJA | ae2stuff                          | 0.7.0.4                            | ae2stuff-0.7.0.4-mc1.12.2.jar                              | None                                     |
	| LCHIJA | projecte                          | 1.12.2-PE1.4.1                     | ProjectE-1.12.2-PE1.4.1.jar                                | None                                     |
	| LCHIJA | tesla                             | 1.0.63                             | Tesla-1.12.2-1.0.63.jar                                    | d476d1b22b218a10d845928d1665d45fce301b27 |
	| LCHIJA | p455w0rdslib                      | 2.3.161                            | p455w0rdslib-1.12.2-2.3.161.jar                            | 186bc454cd122c9c2f1aa4f95611254bcc543363 |
	| LCHIJA | ae2wtlib                          | 1.0.34                             | AE2WTLib-1.12.2-1.0.34.jar                                 | 186bc454cd122c9c2f1aa4f95611254bcc543363 |
	| LCHIJA | forgelin                          | 1.8.4                              | Forgelin-1.8.4.jar                                         | None                                     |
	| LCHIJA | infinitylib                       | 1.12.2-1.12.1                      | infinitylib-1.12.1.jar                                     | None                                     |
	| LCHIJA | agricraft                         | 2.12.0-1.12.2-b2                   | agricraft-2.12.0-1.12.2-b2.jar                             | None                                     |
	| LCHIJA | wasaila                           | 1.0                                | Wasaila-1.0.jar                                            | None                                     |
	| LCHIJA | waila                             | 1.8.26                             | Hwyla-1.8.26-B41_1.12.2.jar                                | None                                     |
	| LCHIJA | mcmultipart                       | 2.5.3                              | MCMultiPart-2.5.3.jar                                      | None                                     |
	| LCHIJA | mekanism                          | 1.12.2-9.8.3.390                   | Mekanism-1.12.2-9.8.3.390.jar                              | None                                     |
	| LCHIJA | aeadditions                       | 1.3.8                              | AEAdditions-1.12.2-1.3.8.jar                               | None                                     |
	| LCHIJA | akashictome                       | 1.2-12                             | AkashicTome-1.2-12.jar                                     | None                                     |
	| LCHIJA | placebo                           | 1.6.0                              | Placebo-1.12.2-1.6.0.jar                                   | None                                     |
	| LCHIJA | apotheosis                        | 1.12.4                             | Apotheosis-1.12.2-1.12.5.jar                               | None                                     |
	| LCHIJA | applecore                         | 3.4.0                              | AppleCore-mc1.12.2-3.4.0.jar                               | None                                     |
	| LCHIJA | appleskin                         | 1.0.14                             | AppleSkin-mc1.12-1.0.14.jar                                | None                                     |
	| LCHIJA | thedragonlib                      | 1.12.2-5.3.0                       | thedragonlib-1.12.2-5.3.0.jar                              | None                                     |
	| LCHIJA | armorplus                         | 1.12.2-11.28.0.69                  | armorplus-1.12.2-11.28.0.69.jar                            | None                                     |
	| LCHIJA | aroma1997core                     | 2.0.0.2.b167                       | Aroma1997Core-1.12.2-2.0.0.2.b167.jar                      | dfbfe4c473253d8c5652417689848f650b2cbe32 |
	| LCHIJA | aroma1997sdimension               | 2.0.0.2.b89                        | Aroma1997s-Dimensional-World-1.12.2-2.0.0.2.b89.jar        | dfbfe4c473253d8c5652417689848f650b2cbe32 |
	| LCHIJA | astralsorcery                     | 1.10.27                            | astralsorcery-1.12.2-1.10.27.jar                           | a0f0b759d895c15ceb3e3bcb5f3c2db7c582edf0 |
	| LCHIJA | attributefix                      | 1.0.10                             | AttributeFix-1.12.2-1.0.10.jar                             | d476d1b22b218a10d845928d1665d45fce301b27 |
	| LCHIJA | audiodeath                        | 0.7.0_1.9-87aeca7                  | audiodeath-1.9-0.7.0.50+87aeca7.jar                        | None                                     |
	| LCHIJA | morphtool                         | 1.2-21                             | Morph-o-Tool-1.2-21.jar                                    | None                                     |
	| LCHIJA | autoreglib                        | 1.3-32                             | AutoRegLib-1.3-32.jar                                      | None                                     |
	| LCHIJA | avaritia                          | 3.3.0                              | Avaritia-1.12.2-3.3.0.37-universal.jar                     | None                                     |
	| LCHIJA | botania                           | r1.10-364                          | Botania r1.10-364.4.jar                                    | None                                     |
	| LCHIJA | avaritiatweaks                    | @VERSION@                          | Avaritia's Complement-1.12.2-1.4.jar                       | None                                     |
	| LCHIJA | base                              | 3.14.0                             | base-1.12.2-3.14.0.jar                                     | None                                     |
	| LCHIJA | bhc                               | 2.0.3                              | baubley-heart-canisters-1.12.2-2.0.3.jar                   | None                                     |
	| LCHIJA | betteradvancements                | 0.1.0.77                           | BetterAdvancements-1.12.2-0.1.0.77.jar                     | None                                     |
	| LCHIJA | betterbuilderswands               | 0.13.2                             | BetterBuildersWands-1.12.2-0.13.2.271+5997513.jar          | None                                     |
	| LCHIJA | betterquesting                    | 3.5.329                            | BetterQuesting-3.5.329.jar                                 | None                                     |
	| LCHIJA | bqt                               | 1.0                                | BetterQuestingTriggerer-1.0.jar                            | None                                     |
	| LCHIJA | bhmenu                            | 1.2                                | BH-Menu-1.12.2-1.3.jar                                     | None                                     |
	| LCHIJA | bibliocraft                       | 2.4.6                              | BiblioCraft[v2.4.6][MC1.12.2].jar                          | None                                     |
	| LCHIJA | biolib                            | 1.1.3                              | biolib-1.1.3.jar                                           | None                                     |
	| LCHIJA | biometweaker                      | 3.2.369                            | BiomeTweaker-1.12.2-3.2.369.jar                            | 631f326344f7f5fd7df7eb940760ebd52b7c9c17 |
	| LCHIJA | blockcraftery                     | 1.12.2-1.3.1                       | blockcraftery-1.12.2-1.3.1.jar                             | None                                     |
	| LCHIJA | guideapi                          | 1.12-2.1.8-63                      | Guide-API-1.12-2.1.8-63.jar                                | None                                     |
	| LCHIJA | bloodmagic                        | 1.12.2-2.4.3-105                   | BloodMagic-1.12.2-2.4.3-105.jar                            | None                                     |
	| LCHIJA | bonsaitrees                       | 1.1.4                              | bonsaitrees-1.1.4-b170.jar                                 | None                                     |
	| LCHIJA | bookshelf                         | 2.3.590                            | Bookshelf-1.12.2-2.3.590.jar                               | d476d1b22b218a10d845928d1665d45fce301b27 |
	| LCHIJA | brokenwings                       | 2.0.0                              | brokenwings-3.0.0.jar                                      | None                                     |
	| LCHIJA | buildinggadgets                   | 2.8.4                              | BuildingGadgets-2.8.4.jar                                  | None                                     |
	| LCHIJA | ceramics                          | 1.12-1.3.7b                        | Ceramics-1.12-1.3.7b.jar                                   | None                                     |
	| LCHIJA | chameleon                         | 1.12-4.1.3                         | Chameleon-1.12-4.1.3.jar                                   | None                                     |
	| LCHIJA | chancecubes                       | 1.12.2-5.0.2.385                   | ChanceCubes-1.12.2-5.0.2.385.jar                           | None                                     |
	| LCHIJA | chickenchunks                     | 2.4.2.74                           | ChickenChunks-1.12.2-2.4.2.74-universal.jar                | f1850c39b2516232a2108a7bd84d1cb5df93b261 |
	| LCHIJA | chiselsandbits                    | 14.33                              | chiselsandbits-14.33.jar                                   | None                                     |
	| LCHIJA | clienttweaks                      | 3.1.11                             | ClientTweaks_1.12.2-3.1.11.jar                             | None                                     |
	| LCHIJA | clumps                            | 3.1.2                              | Clumps-3.1.2.jar                                           | None                                     |
	| LCHIJA | collective                        | 3.0                                | collective-1.12.2-3.0.jar                                  | None                                     |
	| LCHIJA | compacter                         | 1.3.0.3                            | compacter-1.3.0.3-mc1.12.2.jar                             | None                                     |
	| LCHIJA | compactmachines3                  | 3.0.18                             | compactmachines3-1.12.2-3.0.18-b278.jar                    | None                                     |
	| LCHIJA | contenttweaker                    | 1.12.2-4.10.0                      | ContentTweaker-1.12.2-4.10.0.jar                           | None                                     |
	| LCHIJA | controlling                       | 3.0.10                             | Controlling-3.0.10.jar                                     | None                                     |
	| LCHIJA | cookingforblockheads              | 6.5.0                              | CookingForBlockheads_1.12.2-6.5.0.jar                      | None                                     |
	| LCHIJA | copypaste                         | 1.1                                | copypaste-1.1.jar                                          | None                                     |
	| LCHIJA | craftingtweaks                    | 8.1.9                              | CraftingTweaks_1.12.2-8.1.9.jar                            | None                                     |
	| LCHIJA | ctgui                             | 1.0.0                              | CraftTweaker2-1.12-4.1.20.680.jar                          | None                                     |
	| LCHIJA | crafttweakerjei                   | 2.0.3                              | CraftTweaker2-1.12-4.1.20.680.jar                          | None                                     |
	| LCHIJA | creativecore                      | 1.10.0                             | CreativeCore_v1.10.70_mc1.12.2.jar                         | None                                     |
	| LCHIJA | cucumber                          | 1.1.3                              | Cucumber-1.12.2-1.1.3.jar                                  | None                                     |
	| LCHIJA | custommainmenu                    | 2.0.9.1                            | CustomMainMenu-MC1.12.2-2.0.9.1.jar                        | None                                     |
	| LCHIJA | cyclopscore                       | 1.6.7                              | CyclopsCore-1.12.2-1.6.7.jar                               | bd0353b3e8a2810d60dd584e256e364bc3bedd44 |
	| LCHIJA | mousetweaks                       | 2.10.1                             | MouseTweaks-2.10.1-mc1.12.2.jar                            | None                                     |
	| LCHIJA | danknull                          | 1.7.101                            | DankNull-1.12.2-1.7.101.jar                                | 644f38521a349310a5dae0239577dc7beebefaec |
	| LCHIJA | darknesslib                       | 1.1.2                              | DarknessLib-1.12.2-1.1.2.jar                               | 220f10d3a93b3ff5fbaa7434cc629d863d6751b9 |
	| LCHIJA | darkutils                         | 1.8.230                            | DarkUtils-1.12.2-1.8.230.jar                               | d476d1b22b218a10d845928d1665d45fce301b27 |
	| LCHIJA | diethopper                        | 1.1                                | diethopper-1.1.jar                                         | None                                     |
	| LCHIJA | dimensionaledibles                | 1.12.2-1.6.4                       | DimensionalEdibles-1.12.2-1.6.4.jar                        | None                                     |
	| LCHIJA | discordsuite                      | 2.2.4                              | DiscordSuite-2.2.4.jar                                     | None                                     |
	| LCHIJA | eleccore                          | 1.9.453                            | ElecCore-1.12.2-1.9.453.jar                                | None                                     |
	| LCHIJA | embers                            | 1.19                               | EmbersRekindled-1.19.jar                                   | None                                     |
	| LCHIJA | enderiobase                       | 5.2.59                             | EnderIO-1.12.2-5.2.59.jar                                  | None                                     |
	| LCHIJA | enderioconduits                   | 5.2.59                             | EnderIO-1.12.2-5.2.59.jar                                  | None                                     |
	| LCHIJA | enderioconduitsappliedenergistics | 5.2.59                             | EnderIO-1.12.2-5.2.59.jar                                  | None                                     |
	| LCHIJA | opencomputers                     | 1.7.7+5413028                      | OpenComputers-MC1.12.2-1.7.7+5413028.jar                   | None                                     |
	| LCHIJA | enderioconduitsopencomputers      | 5.2.59                             | EnderIO-1.12.2-5.2.59.jar                                  | None                                     |
	| LCHIJA | enderioconduitsrefinedstorage     | 5.2.59                             | EnderIO-1.12.2-5.2.59.jar                                  | None                                     |
	| LCHIJA | enderiointegrationforestry        | 5.2.59                             | EnderIO-1.12.2-5.2.59.jar                                  | None                                     |
	| LCHIJA | enderiointegrationticlate         | 5.2.59                             | EnderIO-1.12.2-5.2.59.jar                                  | None                                     |
	| LCHIJA | ftblib                            | 5.4.7.2                            | FTBLib-5.4.7.2.jar                                         | None                                     |
	| LCHIJA | enderiomachines                   | 5.2.59                             | EnderIO-1.12.2-5.2.59.jar                                  | None                                     |
	| LCHIJA | enderiopowertools                 | 5.2.59                             | EnderIO-1.12.2-5.2.59.jar                                  | None                                     |
	| LCHIJA | enderioendergy                    | 5.2.59                             | EnderIO-endergy-1.12.2-5.2.59.jar                          | None                                     |
	| LCHIJA | enderstorage                      | 2.4.6.137                          | EnderStorage-1.12.2-2.4.6.137-universal.jar                | f1850c39b2516232a2108a7bd84d1cb5df93b261 |
	| LCHIJA | ironchest                         | 1.12.2-7.0.67.844                  | ironchest-1.12.2-7.0.72.847.jar                            | None                                     |
	| LCHIJA | endermanevo                       | 1.0.33                             | EndermanEvolution-1.12.2-1.0.33.jar                        | 186bc454cd122c9c2f1aa4f95611254bcc543363 |
	| LCHIJA | epicsiegemod                      | 13.168                             | EpicSiegeMod-13.168.jar                                    | None                                     |
	| LCHIJA | mikesmodslib                      | 1.0.2                              | MikesModsLib-1.0.2.jar                                     | None                                     |
	| LCHIJA | projectex                         | 1.2.0.40                           | ProjectEX-1.2.0.40.jar                                     | None                                     |
	| LCHIJA | equivalentintegrations            | 0.4.6                              | EquivalentIntegrations-0.4.6.jar                           | None                                     |
	| LCHIJA | erebus                            | 1.0.32                             | Erebus-1.0.32.jar                                          | None                                     |
	| LCHIJA | everlastingabilities              | 1.5.3                              | EverlastingAbilities-1.12.2-1.5.3.jar                      | bd0353b3e8a2810d60dd584e256e364bc3bedd44 |
	| LCHIJA | exnihilocreatio                   | 1.12.2-0.4.7.2                     | exnihilocreatio-1.12.2-0.4.7.2.jar                         | None                                     |
	| LCHIJA | hammercore                        | 2.0.6.32                           | HammerLib-1.12.2-2.0.6.32.jar                              | 9f5e2a811a8332a842b34f6967b7db0ac4f24856 |
	| LCHIJA | expequiv                          | 12.3.17                            | ExpandedEquivalence-1.12.2-12.3.17.jar                     | 9f5e2a811a8332a842b34f6967b7db0ac4f24856 |
	| LCHIJA | extendedcrafting                  | 1.7.0                              | ExtendedCrafting-Nomifactory-Edition-1.7.0.jar             | None                                     |
	| LCHIJA | galacticraftcore                  | 4.0.2.280                          | GalacticraftCore-1.12.2-4.0.2.280.jar                      | None                                     |
	| LCHIJA | galacticraftplanets               | 4.0.2.280                          | Galacticraft-Planets-1.12.2-4.0.2.280.jar                  | None                                     |
	| LCHIJA | mjrlegendslib                     | 1.12.2-1.2.1                       | MJRLegendsLib-1.12.2-1.2.1.jar                             | b02331787272ec3515ebe63ecdeea0d746653468 |
	| LCHIJA | extraplanets                      | 1.12.2-0.7.4                       | ExtraPlanets-1.12.2-0.7.4.jar                              | b02331787272ec3515ebe63ecdeea0d746653468 |
	| LCHIJA | extrautils2                       | 1.0                                | extrautils2-1.12-1.9.9.jar                                 | None                                     |
	| LCHIJA | zerocore                          | 1.12.2-0.1.2.9                     | zerocore-1.12.2-0.1.2.9.jar                                | None                                     |
	| LCHIJA | bigreactors                       | 1.12.2-0.4.5.68                    | ExtremeReactors-1.12.2-0.4.5.68.jar                        | None                                     |
	| LCHIJA | farmingforblockheads              | 3.1.28                             | FarmingForBlockheads_1.12.2-3.1.28.jar                     | None                                     |
	| LCHIJA | fencejumper                       | 1.0.5                              | fencejumper-1.12-1.0.5.jar                                 | None                                     |
	| LCHIJA | foamfix                           | @VERSION@                          | foamfix-0.10.15-1.12.2.jar                                 | None                                     |
	| LCHIJA | forgemultipartcbe                 | 2.6.2.83                           | ForgeMultipart-1.12.2-2.6.2.83-universal.jar               | f1850c39b2516232a2108a7bd84d1cb5df93b261 |
	| LCHIJA | microblockcbe                     | 2.6.2.83                           | ForgeMultipart-1.12.2-2.6.2.83-universal.jar               | None                                     |
	| LCHIJA | minecraftmultipartcbe             | 2.6.2.83                           | ForgeMultipart-1.12.2-2.6.2.83-universal.jar               | None                                     |
	| LCHIJA | ftbbackups                        | 1.1.0.1                            | FTBBackups-1.1.0.1.jar                                     | None                                     |
	| LCHIJA | ftbutilities                      | 5.4.1.131                          | FTBUtilities-5.4.1.131.jar                                 | None                                     |
	| LCHIJA | furnaceoverhaul                   | 2.2.2                              | furnaceoverhaul-1.12.2-2.2.2.jar                           | None                                     |
	| LCHIJA | galacticrafttweaker               | 1.12.2-1.0.3                       | GalacticraftTweaker-1.12.2-1.0.3.jar                       | b02331787272ec3515ebe63ecdeea0d746653468 |
	| LCHIJA | gardenofglass                     | sqrt(-1)                           | GardenOfGlass.jar                                          | None                                     |
	| LCHIJA | grue                              | 1.8.1                              | Grue-1.12.2-1.8.1.jar                                      | 220f10d3a93b3ff5fbaa7434cc629d863d6751b9 |
	| LCHIJA | gunpowderlib                      | 1.12.2-1.1                         | GunpowderLib-1.12.2-1.1.jar                                | 4ffa87db52cf086d00ecc4853a929367b1c39b5c |
	| LCHIJA | huntingdim                        | 1.0.42                             | HuntingDimension-1.12.2-1.0.42.jar                         | d476d1b22b218a10d845928d1665d45fce301b27 |
	| LCHIJA | immersiveengineering              | 0.12-98                            | ImmersiveEngineering-0.12-98.jar                           | None                                     |
	| LCHIJA | immersivepetroleum                | 1.1.10                             | immersivepetroleum-1.12.2-1.1.10.jar                       | None                                     |
	| LCHIJA | teslacorelib                      | 1.0.18                             | tesla-core-lib-1.12.2-1.0.18.jar                           | d476d1b22b218a10d845928d1665d45fce301b27 |
	| LCHIJA | industrialforegoing               | 1.12.2-1.12.2                      | industrialforegoing-1.12.2-1.12.13-237.jar                 | None                                     |
	| LCHIJA | lunatriuscore                     | 1.2.0.42                           | LunatriusCore-1.12.2-1.2.0.42-universal.jar                | None                                     |
	| LCHIJA | ingameinfoxml                     | 2.8.2.94                           | InGameInfoXML-1.12.2-2.8.2.94-universal.jar                | None                                     |
	| LCHIJA | instantunify                      | 1.1.2                              | instantunify-1.12.2-1.1.2.jar                              | None                                     |
	| LCHIJA | mysticalagriculture               | 1.7.5                              | MysticalAgriculture-1.12.2-1.7.5.jar                       | None                                     |
	| LCHIJA | mysticalagradditions              | 1.3.2                              | MysticalAgradditions-1.12.2-1.3.2.jar                      | None                                     |
	| LCHIJA | natura                            | 1.12.2-4.3.2.69                    | natura-1.12.2-4.3.2.69.jar                                 | None                                     |
	| LCHIJA | nuclearcraft                      | 2.18zzz                            | NuclearCraft-2.18zzz-1.12.2.jar                            | None                                     |
	| LCHIJA | harvestcraft                      | 1.12.2zb                           | Pam's HarvestCraft 1.12.2zg.jar                            | None                                     |
	| LCHIJA | randomthings                      | 4.2.7.4                            | RandomThings-MC1.12.2-4.2.7.4.jar                          | d72e0dd57935b3e9476212aea0c0df352dd76291 |
	| LCHIJA | mcjtylib_ng                       | 3.5.4                              | mcjtylib-1.12-3.5.4.jar                                    | None                                     |
	| LCHIJA | rftools                           | 7.73                               | rftools-1.12-7.73.jar                                      | None                                     |
	| LCHIJA | integrationforegoing              | 1.12.2-1.11                        | IntegrationForegoing-1.12.2-1.11.jar                       | 4ffa87db52cf086d00ecc4853a929367b1c39b5c |
	| LCHIJA | inventorytweaks                   | 1.64+dev.151.822d839               | InventoryTweaks-1.64+dev.151.jar                           | 55d2cd4f5f0961410bf7b91ef6c6bf00a766dcbe |
	| LCHIJA | journeymap                        | 1.12.2-5.7.1                       | journeymap-1.12.2-5.7.1.jar                                | None                                     |
	| LCHIJA | jee                               | 1.0.8                              | JustEnoughEnergistics-1.12.2-1.0.8.jar                     | None                                     |
	| LCHIJA | justenoughpetroleum               | 0.1                                | JustEnoughPetroleum-0.1.jar                                | None                                     |
	| LCHIJA | karatgarden                       | 0.1.4                              | KaratGarden-0.1.4-[1.12.2].jar                             | None                                     |
	| LCHIJA | kleeslabs                         | 5.4.12                             | KleeSlabs_1.12.2-5.4.12.jar                                | None                                     |
	| LCHIJA | kc                                | 1.12                               | knobcontrol-1.12-4.0.20.jar                                | None                                     |
	| LCHIJA | libraryex                         | 1.2.2                              | LibraryEx-1.12.2-1.2.2.jar                                 | None                                     |
	| LCHIJA | lootbags                          | 2.5.8.5                            | LootBags-1.12.2-2.5.8.5.jar                                | None                                     |
	| LCHIJA | lttweaker                         | 1.1.17                             | LootTableTweaker-1.12.2-1.1.17.jar                         | d476d1b22b218a10d845928d1665d45fce301b27 |
	| LCHIJA | lordcraft                         | 1.0.0                              | Lord Craft 2.10.3.jar                                      | None                                     |
	| LCHIJA | lostcities                        | 2.0.22                             | lostcities-1.12-2.0.22.jar                                 | None                                     |
	| LCHIJA | magneticraft                      | 2.8.5                              | Magneticraft_1.12-2.8.5-dev.jar                            | None                                     |
	| LCHIJA | manavisualizer                    | r1.0-1                             | ManaVisualizer-r1.0-1.jar                                  | None                                     |
	| LCHIJA | mapgadgets                        | @VERSION@                          | Mapmaker's Gadgets-1.2_for_1.12.x.jar                      | None                                     |
	| LCHIJA | matc                              | 1.0.1-hotfix                       | matc-1.0.1-hotfix.jar                                      | None                                     |
	| LCHIJA | materialis                        | 1.2.5                              | materialis-1.12.2-1.2.5.jar                                | None                                     |
	| LCHIJA | mekanismgenerators                | 1.12.2-9.8.3.390                   | MekanismGenerators-1.12.2-9.8.3.390.jar                    | None                                     |
	| LCHIJA | mekanismtools                     | 1.12.2-9.8.3.390                   | MekanismTools-1.12.2-9.8.3.390.jar                         | None                                     |
	| LCHIJA | mob_grinding_utils                | 0.3.13                             | MobGrindingUtils-0.3.13.jar                                | None                                     |
	| LCHIJA | modelloader                       | 1.1.7                              | modelloader-1.1.7.jar                                      | None                                     |
	| LCHIJA | modnametooltip                    | 1.10.1                             | modnametooltip_1.12.2-1.10.1.jar                           | None                                     |
	| LCHIJA | modularmachinery                  | 1.11.1                             | modularmachinery-1.12.2-1.11.1.jar                         | a0f0b759d895c15ceb3e3bcb5f3c2db7c582edf0 |
	| LCHIJA | moreoverlays                      | 1.15.1                             | moreoverlays-1.15.1-mc1.12.2.jar                           | None                                     |
	| LCHIJA | morpheus                          | 1.12.2-3.5.106                     | Morpheus-1.12.2-3.5.106.jar                                | None                                     |
	| LCHIJA | mputils                           | 1.5.6                              | MPUtils-1.12.2-1.5.7.jar                                   | None                                     |
	| LCHIJA | mpbasic                           | 1.4.7                              | mpbasic-1.12.2-1.4.11.jar                                  | None                                     |
	| LCHIJA | mrtjpcore                         | 2.1.4.43                           | MrTJPCore-1.12.2-2.1.4.43-universal.jar                    | None                                     |
	| LCHIJA | neat                              | 1.4-17                             | Neat 1.4-17.jar                                            | None                                     |
	| LCHIJA | projectred-core                   | 4.9.4.120                          | ProjectRed-1.12.2-4.9.4.120-Base.jar                       | None                                     |
	| LCHIJA | projectred-exploration            | 4.9.4.120                          | ProjectRed-1.12.2-4.9.4.120-world.jar                      | None                                     |
	| LCHIJA | wawla                             | 2.6.275                            | Wawla-1.12.2-2.6.275.jar                                   | d476d1b22b218a10d845928d1665d45fce301b27 |
	| LCHIJA | netherendingores                  | 1.12.2-1.4.2                       | Netherending-Ores-1.12.2-1.4.2.jar                         | None                                     |
	| LCHIJA | netherex                          | 2.2.5                              | NetherEx-1.12.2-2.2.5.jar                                  | None                                     |
	| LCHIJA | nmsot                             | 1.2.2-mc1.12.2                     | NoMobSpawningOnTrees-1.2.2-mc1.12.2.jar                    | None                                     |
	| LCHIJA | neid                              | 1.5.4.4                            | NotEnoughIDs-1.5.4.4.jar                                   | None                                     |
	| LCHIJA | oauth                             | 1.06.4                             | oauth-1.06.4.jar                                           | None                                     |
	| LCHIJA | omlib                             | 3.1.5-256                          | omlib-1.12.2-3.1.5-256.jar                                 | None                                     |
	| LCHIJA | ompd                              | 3.1.1-76                           | ompd-1.12.2-3.1.1-76.jar                                   | None                                     |
	| LCHIJA | openmods                          | 0.12.2                             | OpenModsLib-1.12.2-0.12.2.jar                              | d2a9a8e8440196e26a268d1f3ddc01b2e9c572a5 |
	| LCHIJA | openblocks                        | 1.8.1                              | OpenBlocks-1.12.2-1.8.1.jar                                | d2a9a8e8440196e26a268d1f3ddc01b2e9c572a5 |
	| LCHIJA | openmodularturrets                | 3.1.14-382                         | openmodularturrets-1.12.2-3.1.14-382.jar                   | None                                     |
	| LCHIJA | oreexcavation                     | 1.4.150                            | OreExcavation-1.4.150.jar                                  | None                                     |
	| LCHIJA | overloaded                        | 0.0.59                             | Overloaded-1.12.2-0.0.59.jar                               | None                                     |
	| LCHIJA | overpoweredarmorbar               | @VERSION@                          | overloadedarmorbar-1.0.4g.jar                              | None                                     |
	| LCHIJA | packmode                          | 1.2.0                              | packmode-1.12.2-1.2.0.jar                                  | None                                     |
	| LCHIJA | packmodemenu                      | 1.0.6                              | PackModeMenu-1.0.6.jar                                     | None                                     |
	| LCHIJA | patchouli                         | 1.0-23.6                           | Patchouli-1.0-23.6.jar                                     | None                                     |
	| LCHIJA | pneumaticcraft                    | 1.12.2-0.11.15-398                 | pneumaticcraft-repressurized-1.12.2-0.11.15-398.jar        | None                                     |
	| LCHIJA | portality                         | 1.0-SNAPSHOT                       | portality-1.12.2-1.2.3-15.jar                              | None                                     |
	| LCHIJA | progressivebosses                 | 1.5.4                              | ProgressiveBosses-1.5.4-mc1.12.x.jar                       | None                                     |
	| LCHIJA | projectintelligence               | 1.0.9                              | ProjectIntelligence-1.12.2-1.0.9.28-universal.jar          | None                                     |
	| LCHIJA | projectred-expansion              | 4.9.4.120                          | ProjectRed-1.12.2-4.9.4.120-mechanical.jar                 | None                                     |
	| LCHIJA | projectred-relocation             | 4.9.4.120                          | ProjectRed-1.12.2-4.9.4.120-mechanical.jar                 | None                                     |
	| LCHIJA | projectred-transportation         | 4.9.4.120                          | ProjectRed-1.12.2-4.9.4.120-mechanical.jar                 | None                                     |
	| LCHIJA | quantumflux                       | 2.0.18                             | quantumflux-1.12.2-2.0.18.jar                              | None                                     |
	| LCHIJA | reborncore                        | 3.19.5                             | RebornCore-1.12.2-3.19.5-universal.jar                     | None                                     |
	| LCHIJA | quantumstorage                    | 4.7.0                              | QuantumStorage-1.12-4.7.0.jar                              | None                                     |
	| LCHIJA | redstonearsenal                   | 2.6.6                              | RedstoneArsenal-1.12.2-2.6.6.1-universal.jar               | None                                     |
	| LCHIJA | xreliquary                        | 1.12.2-1.3.4.796                   | Reliquary-1.12.2-1.3.4.796.jar                             | None                                     |
	| LCHIJA | resourceloader                    | 1.5.3                              | ResourceLoader-MC1.12.1-1.5.3.jar                          | d72e0dd57935b3e9476212aea0c0df352dd76291 |
	| LCHIJA | restrictedportals                 | 1.12-0.6.3                         | restrictedportals-1.12-0.6.3.jar                           | None                                     |
	| LCHIJA | rftoolscontrol                    | 2.0.2                              | rftoolsctrl-1.12-2.0.2.jar                                 | None                                     |
	| LCHIJA | rftoolsdim                        | 5.71                               | rftoolsdim-1.12-5.71.jar                                   | None                                     |
	| LCHIJA | riteclicker                       | 1.12_1                             | riteclicker-1.12.2_2.jar                                   | None                                     |
	| LCHIJA | rockcandy                         | 1.12.2-3.00                        | rockcandy-1.12.2-3.0.0.jar                                 | None                                     |
	| LCHIJA | simplevoidworld                   | 1.2.0.9                            | Simple-Void-World-1.12-1.2.0.9-universal.jar               | None                                     |
	| LCHIJA | simplesponge                      | 3.7                                | SimpleSponge-1.12.2-3.7.jar                                | 4ffa87db52cf086d00ecc4853a929367b1c39b5c |
	| LCHIJA | simple_trophies                   | 1.2.2                              | simpletrophies-1.2.2.1.jar                                 | None                                     |
	| LCHIJA | thermaldynamics                   | 2.5.6                              | ThermalDynamics-1.12.2-2.5.6.1-universal.jar               | None                                     |
	| LCHIJA | simplyjetpacks                    | 1.12.2-2.2.20.0                    | SimplyJetpacks2-1.12.2-2.2.20.0.jar                        | None                                     |
	| LCHIJA | skylandsforge                     | 1.12.2_0.2                         | SkyLandsForge-1.12.2_0.2.jar                               | None                                     |
	| LCHIJA | solarflux                         | 12.4.11                            | SolarFluxReborn-1.12.2-12.4.11.jar                         | 9f5e2a811a8332a842b34f6967b7db0ac4f24856 |
	| LCHIJA | soot                              | 1.10-hotfix                        | Soot-1.10-hotfix.jar                                       | None                                     |
	| LCHIJA | stackie                           | 1.6.0.48                           | Stackie-1.12.2-1.6.0.48-universal.jar                      | None                                     |
	| LCHIJA | stacksize                         | 1.1                                | stacksize-1.12.2-1.0.jar                                   | None                                     |
	| LCHIJA | bq_standard                       | 3.4.173                            | StandardExpansion-3.4.173.jar                              | None                                     |
	| LCHIJA | storagedrawers                    | 5.2.2                              | StorageDrawers-1.12.2-5.4.2.jar                            | None                                     |
	| LCHIJA | teslafied                         | 1.1.1                              | teslafied-1.12-1.1.1.jar                                   | None                                     |
	| LCHIJA | thermalinnovation                 | 0.3.6                              | ThermalInnovation-1.12.2-0.3.6.1-universal.jar             | None                                     |
	| LCHIJA | thermalsolars                     | 1.12.2 V1.9.5                      | thermalsolars-1.12.2-1.9.5.jar                             | None                                     |
	| LCHIJA | tinkers_reforged                  | 1.5.6                              | tinkers_reforged-1.5.6.jar                                 | None                                     |
	| LCHIJA | tcomplement                       | 1.12.2-0.4.3                       | TinkersComplement-1.12.2-0.4.3.jar                         | None                                     |
	| LCHIJA | tinkertoolleveling                | 1.12.2-1.1.0.DEV.b23e769           | TinkerToolLeveling-1.12.2-1.1.0.jar                        | None                                     |
	| LCHIJA | tp                                | 3.2.34                             | tinyprogressions-1.12.2-3.3.34-Release.jar                 | None                                     |
	| LCHIJA | tipthescales                      | 1.0.4                              | TipTheScales-1.12.2-1.0.4.jar                              | None                                     |
	| LCHIJA | toastcontrol                      | 1.8.1                              | Toast Control-1.12.2-1.8.1.jar                             | None                                     |
	| LCHIJA | translocators                     | 2.5.2.81                           | Translocators-1.12.2-2.5.2.81-universal.jar                | f1850c39b2516232a2108a7bd84d1cb5df93b261 |
	| LCHIJA | ts2k16                            | 1.2.10                             | TS2K16-1.2.10.jar                                          | None                                     |
	| LCHIJA | wailaharvestability               | 1.1.12                             | WailaHarvestability-mc1.12-1.1.12.jar                      | None                                     |
	| LCHIJA | wanionlib                         | 1.12.2-2.9                         | WanionLib-1.12.2-2.9.jar                                   | None                                     |
	| LCHIJA | waystones                         | 4.1.0                              | Waystones_1.12.2-4.1.0.jar                                 | None                                     |
	| LCHIJA | wct                               | 3.12.97                            | WirelessCraftingTerminal-1.12.2-3.12.97.jar                | 186bc454cd122c9c2f1aa4f95611254bcc543363 |
	| LCHIJA | wit                               | 1.0.2                              | WirelessInterfaceTerminal-1.12.2-1.0.2.jar                 | 186bc454cd122c9c2f1aa4f95611254bcc543363 |
	| LCHIJA | witherskelefix                    | 2.6.3                              | WitherSkeletonTweaks-1.12.2-2.6.3.jar                      | None                                     |
	| LCHIJA | woot                              | 1.12.2-1.4.11                      | woot-1.12.2-1.4.11.jar                                     | None                                     |
	| LCHIJA | xnet                              | 1.8.2                              | xnet-1.12-1.8.2.jar                                        | None                                     |
	| LCHIJA | yabba                             | 1.1.2.54                           | YABBA-1.1.2.54.jar                                         | None                                     |
	| LCHIJA | ynot                              | 0.2.4                              | YNot-0.2.4.jar                                             | None                                     |
	| LCHIJA | nofog                             | 1.12.2-1.12.2-1.0.3.0              | NoFog-1.12.2b3.jar                                         | 0bf221d944c89aaf3ccb7b8315148f222be50739 |
	| LCHIJA | phosphor-lighting                 | 1.12.2-0.2.7                       | phosphor-forge-mc1.12.2-0.2.7-universal.jar                | None                                     |
	| LCHIJA | eleccoreloader                    | 1.9.453                            | ElecCore-1.12.2-1.9.453.jar                                | None                                     |
	| LCHIJA | moofluids                         | 1.12.2-1.8.12.02a                  | MooFluids-1.12.2-1.8.12.02a.jar                            | None                                     |
	| LCHIJA | mysticallib                       | 1.12.2-1.13.0                      | mysticallib-1.12.2-1.13.0.jar                              | None                                     |
	| LCHIJA | teslacorelib_registries           | 1.0.18                             | tesla-core-lib-1.12.2-1.0.18.jar                           | None                                     |
	| LCHIJA | tweakersconstructpostload         | 1.12.2-1.6.1                       | tweakersconstruct-1.12.2-1.6.1.jar                         | None                                     |
	| LCHIJA | unidict                           | 1.12.2-3.0.10                      | UniDict-1.12.2-3.0.10.jar                                  | None                                     |

	Loaded coremods (and transformers): 
IELoadingPlugin (ImmersiveEngineering-core-0.12-98.jar)
  blusunrize.immersiveengineering.common.asm.IEClassTransformer
MekanismCoremod (Mekanism-1.12.2-9.8.3.390.jar)
  mekanism.coremod.KeybindingMigrationHelper
ItemPatchingLoader (ItemPhysic_Full_1.4.37_mc1.12.2.jar)
  com.creativemd.itemphysic.ItemTransformer
TransformerLoader (OpenComputers-MC1.12.2-1.7.7+5413028.jar)
  li.cil.oc.common.asm.ClassTransformer
MicdoodlePlugin (MicdoodleCore-1.12.2-4.0.2.280.jar)
  micdoodle8.mods.miccore.MicdoodleTransformer
PhosphorFMLLoadingPlugin (phosphor-forge-mc1.12.2-0.2.7-universal.jar)
  
Quark Plugin (Quark-r1.6-179.jar)
  vazkii.quark.base.asm.ClassTransformer
AppleCore (AppleCore-mc1.12.2-3.4.0.jar)
  squeek.applecore.asm.TransformerModuleHandler
BiomeTweakerCore (BiomeTweakerCore-1.12.2-1.0.39.jar)
  me.superckl.biometweakercore.BiomeTweakerASMTransformer
UniDictCoreMod (UniDict-1.12.2-3.0.10.jar)
  wanion.unidict.core.UniDictCoreModTransformer
EnderCorePlugin (EnderCore-1.12.2-0.5.76-core.jar)
  com.enderio.core.common.transform.EnderCoreTransformer
  com.enderio.core.common.transform.SimpleMixinPatcher
LoadingPlugin (ResourceLoader-MC1.12.1-1.5.3.jar)
  lumien.resourceloader.asm.ClassTransformer
CoreMod (Aroma1997Core-1.12.2-2.0.0.2.b167.jar)
  
Inventory Tweaks Coremod (InventoryTweaks-1.64+dev.151.jar)
  invtweaks.forge.asm.ContainerTransformer
LoadingPlugin (RandomThings-MC1.12.2-4.2.7.4.jar)
  lumien.randomthings.asm.ClassTransformer
RandomPatches (randompatches-1.12.2-1.22.1.10.jar)
  com.therandomlabs.randompatches.core.RPTransformer
Do not report to Forge! (If you haven't disabled the FoamFix coremod, try disabling it in the config! Note that this bit of text will still appear.) (foamfix-0.10.15-1.12.2.jar)
  pl.asie.foamfix.coremod.FoamFixTransformer
ForgelinPlugin (Forgelin-1.8.4.jar)
  
CreativePatchingLoader (CreativeCore_v1.10.70_mc1.12.2.jar)
  
OpenModsCorePlugin (OpenModsLib-1.12.2-0.12.2.jar)
  openmods.core.OpenModsClassTransformer
Ar_CorePlugin (additionalresources-1.9.4-0.2.0.28+47cd0bd_signed.jar)
  
ApotheosisCore (Apotheosis-1.12.2-1.12.5.jar)
  shadows.ApotheosisTransformer
CTMCorePlugin (CTM-MC1.12.2-1.0.2.31.jar)
  team.chisel.ctm.client.asm.CTMTransformer
Plugin (NotEnoughIDs-1.5.4.4.jar)
  ru.fewizz.neid.asm.Transformer
AstralCore (astralsorcery-1.12.2-1.10.27.jar)
  
HCASM (HammerLib-1.12.2-2.0.6.32.jar)
  com.zeitheron.hammercore.asm.HammerCoreTransformer
	GL info: ' Vendor: 'NVIDIA Corporation' Version: '4.6.0 NVIDIA 516.94' Renderer: 'NVIDIA GeForce GTX 1070/PCIe/SSE2'
	OpenModsLib class transformers: [llama_null_fix:FINISHED],[horse_base_null_fix:FINISHED],[pre_world_render_hook:FINISHED],[player_render_hook:FINISHED],[horse_null_fix:FINISHED]
	Ender IO: No known problems detected.
	Authlib is : /C:/Users/henni/curseforge/minecraft/Install/libraries/com/mojang/authlib/1.5.25/authlib-1.5.25.jar

	!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
	!!!You are looking at the diagnostics information, not at the crash.       !!!
	!!!Scroll up until you see the line with '---- Minecraft Crash Report ----'!!!
	!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

	Pulsar/tconstruct loaded Pulses: 
		- TinkerCommons (Enabled/Forced)
		- TinkerWorld (Enabled/Not Forced)
		- TinkerTools (Enabled/Not Forced)
		- TinkerHarvestTools (Enabled/Forced)
		- TinkerMeleeWeapons (Enabled/Forced)
		- TinkerRangedWeapons (Enabled/Forced)
		- TinkerModifiers (Enabled/Forced)
		- TinkerSmeltery (Enabled/Not Forced)
		- TinkerGadgets (Enabled/Not Forced)
		- TinkerOredict (Enabled/Forced)
		- TinkerIntegration (Enabled/Forced)
		- TinkerFluids (Enabled/Forced)
		- TinkerMaterials (Enabled/Forced)
		- TinkerModelRegister (Enabled/Forced)
		- chiselIntegration (Enabled/Not Forced)
		- chiselsandbitsIntegration (Enabled/Not Forced)
		- craftingtweaksIntegration (Enabled/Not Forced)
		- wailaIntegration (Enabled/Not Forced)
		- quarkIntegration (Enabled/Not Forced)

	AE2 Version: stable rv6-stable-7-extended_life-v0.53.8 for Forge 14.23.5.2847
	HammerCore Debug Information: 
		Dependent Mods:
			-Expanded Equivalence (expequiv) @ 12.3.17

	Pulsar/natura loaded Pulses: 
		- NaturaCommons (Enabled/Forced)
		- NaturaOverworld (Enabled/Not Forced)
		- NaturaNether (Enabled/Not Forced)
		- NaturaDecorative (Enabled/Not Forced)
		- NaturaTools (Enabled/Not Forced)
		- NaturaEntities (Enabled/Not Forced)
		- NaturaOredict (Enabled/Forced)
		- NaturaWorld (Enabled/Not Forced)
		- craftingtweaksIntegration (Enabled/Not Forced)

	Pulsar/tcomplement loaded Pulses: 
		- ModuleCommons (Enabled/Forced)
		- ModuleMelter (Enabled/Not Forced)
		- ModuleArmor (Enabled/Not Forced)
		- ModuleSteelworks (Enabled/Not Forced)
		- CeramicsPlugin (Enabled/Not Forced)
		- ChiselPlugin (Enabled/Not Forced)
		- ExNihiloPlugin (Enabled/Not Forced)
		- ToolLevelingPlugin (Enabled/Not Forced)
		- Oredict (Enabled/Forced)

	List of loaded APIs: 
		* AbyssalCraftAPI (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|Biome (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|Block (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|Caps (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|Condition (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|Disruption (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|Energy (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|Entity (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|Event (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|Integration (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|Internal (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|Item (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|Necronomicon (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|Recipe (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|Rending (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|Ritual (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|Spell (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|Structure (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|Transfer (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* AbyssalCraftAPI|TransferCaps (1.30.0) from AbyssalCraft-1.12.2-1.10.4.jar
		* actuallyadditionsapi (34) from ActuallyAdditions-1.12.2-r152.jar
		* ae2wtlib|API (1.0.34) from AE2WTLib-1.12.2-1.0.34.jar
		* AgriCraftAPI (1.0) from agricraft-2.12.0-1.12.2-b2.jar
		* AppleCoreAPI (3.4.0) from AppleCore-mc1.12.2-3.4.0.jar
		* appliedenergistics2|API (rv6) from appliedenergistics2-rv6-stable-7-extended_life-v0.53.8.jar
		* ArmorPlusApi (2.1) from armorplus-1.12.2-11.28.0.69.jar
		* Base|API (1.0.0) from base-1.12.2-3.14.0.jar
		* Baubles|API (1.4.0.2) from Baubles-1.12-1.5.2.jar
		* betteradvancements|API (0.1.0.77) from BetterAdvancements-1.12.2-0.1.0.77.jar
		* BetterQuesting|API (3.2) from BetterQuesting-3.5.329.jar
		* BetterQuesting|API2 (3.1) from BetterQuesting-3.5.329.jar
		* BetterWithModsAPI (Beta 0.6) from AppleSkin-mc1.12-1.0.14.jar
		* bigreactors|API (4.0.1) from ExtremeReactors-1.12.2-0.4.5.68.jar
		* BiomeTweakerAPI (1.8.369) from BiomeTweaker-1.12.2-3.2.369.jar
		* BiomeTweakerAPI|block (1.8.369) from BiomeTweaker-1.12.2-3.2.369.jar
		* BiomeTweakerAPI|event (1.8.369) from BiomeTweaker-1.12.2-3.2.369.jar
		* BiomeTweakerAPI|property (1.8.369) from BiomeTweaker-1.12.2-3.2.369.jar
		* BiomeTweakerAPI|script (1.8.369) from BiomeTweaker-1.12.2-3.2.369.jar
		* BiomeTweakerAPI|script|object (1.8.369) from BiomeTweaker-1.12.2-3.2.369.jar
		* BiomeTweakerAPI|script|pack (1.8.369) from BiomeTweaker-1.12.2-3.2.369.jar
		* BiomeTweakerAPI|script|wrapper (1.8.369) from BiomeTweaker-1.12.2-3.2.369.jar
		* BiomeTweakerAPI|world|gen|feature (1.8.369) from BiomeTweaker-1.12.2-3.2.369.jar
		* bloodmagic-api (2.0.0) from BloodMagic-1.12.2-2.4.3-105.jar
		* BotaniaAPI (93) from Botania r1.10-364.4.jar
		* Chisel-API (0.0.1) from Chisel-MC1.12.2-1.0.2.45.jar
		* ChiselAPI|Carving (0.0.1) from Chisel-MC1.12.2-1.0.2.45.jar
		* ChiselsAndBitsAPI (14.25.0) from chiselsandbits-14.33.jar
		* cofhapi (2.5.0) from CoFHCore-1.12.2-4.6.6.1-universal.jar
		* CraftingTweaks|API (4.1) from CraftingTweaks_1.12.2-8.1.9.jar
		* ctm-api (0.1.0) from CTM-MC1.12.2-1.0.2.31.jar
		* ctm-api-events (0.1.0) from CTM-MC1.12.2-1.0.2.31.jar
		* ctm-api-models (0.1.0) from CTM-MC1.12.2-1.0.2.31.jar
		* ctm-api-textures (0.1.0) from CTM-MC1.12.2-1.0.2.31.jar
		* ctm-api-utils (0.1.0) from CTM-MC1.12.2-1.0.2.31.jar
		* DarknessLibAPI (1.1.0) from DarknessLib-1.12.2-1.1.2.jar
		* DarknessLibAPI|Cap (1.1.0) from DarknessLib-1.12.2-1.1.2.jar
		* DarknessLibAPI|Internal (1.1.0) from DarknessLib-1.12.2-1.1.2.jar
		* DraconicEvolution|API (1.3) from Draconic-Evolution-1.12.2-2.3.28.354-universal.jar
		* ElecCoreAPI (1.0.0) from ElecCore-1.12.2-1.9.453.jar
		* EmbersAPI (0.1) from EmbersRekindled-1.19.jar
		* enderioapi (4.0.0) from EnderIO-1.12.2-5.2.59.jar
		* enderioapi|addon (4.0.0) from EnderIO-1.12.2-5.2.59.jar
		* enderioapi|capacitor (4.0.0) from EnderIO-1.12.2-5.2.59.jar
		* enderioapi|conduits (4.0.0) from EnderIO-1.12.2-5.2.59.jar
		* enderioapi|farm (4.0.0) from EnderIO-1.12.2-5.2.59.jar
		* enderioapi|redstone (4.0.0) from EnderIO-1.12.2-5.2.59.jar
		* enderioapi|teleport (4.0.0) from EnderIO-1.12.2-5.2.59.jar
		* enderioapi|tools (4.0.0) from EnderIO-1.12.2-5.2.59.jar
		* enderioapi|upgrades (4.0.0) from EnderIO-1.12.2-5.2.59.jar
		* EpicSiegeMod|API (1.0) from EpicSiegeMod-13.168.jar
		* farmingforblockheads|api (1.0) from FarmingForBlockheads_1.12.2-3.1.28.jar
		* Galacticraft API (1.2) from GalacticraftCore-1.12.2-4.0.2.280.jar
		* Guide-API|API (2.0.0) from Guide-API-1.12-2.1.8-63.jar
		* ImmersiveEngineering|API (1.0) from ImmersiveEngineering-0.12-98.jar
		* ImmersiveEngineering|ImmersiveFluxAPI (1.0) from ImmersiveEngineering-0.12-98.jar
		* industrialforegoingapi (5) from industrialforegoing-1.12.2-1.12.13-237.jar
		* journeymap|client-api (1.4) from journeymap-1.12.2-5.7.1.jar
		* journeymap|client-api-display (1.4) from journeymap-1.12.2-5.7.1.jar
		* journeymap|client-api-event (1.4) from journeymap-1.12.2-5.7.1.jar
		* journeymap|client-api-model (1.4) from journeymap-1.12.2-5.7.1.jar
		* journeymap|client-api-util (1.4) from journeymap-1.12.2-5.7.1.jar
		* JustEnoughItemsAPI (4.13.0) from jei_1.12.2-4.16.1.302.jar
		* MagneticraftAPI (1.0.0) from Magneticraft_1.12-2.8.5-dev.jar
		* MekanismAPI|core (9.8.1) from Mekanism-1.12.2-9.8.3.390.jar
		* MekanismAPI|energy (9.8.1) from Mekanism-1.12.2-9.8.3.390.jar
		* MekanismAPI|gas (9.8.1) from Mekanism-1.12.2-9.8.3.390.jar
		* MekanismAPI|infuse (9.8.1) from Mekanism-1.12.2-9.8.3.390.jar
		* MekanismAPI|laser (9.8.1) from Mekanism-1.12.2-9.8.3.390.jar
		* MekanismAPI|transmitter (9.8.1) from Mekanism-1.12.2-9.8.3.390.jar
		* MekanismAPI|util (9.0.0) from Mekanism-1.12.2-9.8.3.390.jar
		* Model-Loader (1.1.0) from modelloader-1.1.7.jar
		* Model-Loader-Vectors (1.0.0) from modelloader-1.1.7.jar
		* MouseTweaks|API (1.0) from MouseTweaks-2.10.1-mc1.12.2.jar
		* openblocks|api (1.2) from OpenBlocks-1.12.2-1.8.1.jar
		* opencomputersapi|component (7.0.0-alpha) from OpenComputers-MC1.12.2-1.7.7+5413028.jar
		* opencomputersapi|core (7.0.0-alpha) from OpenComputers-MC1.12.2-1.7.7+5413028.jar
		* opencomputersapi|driver (7.0.0-alpha) from OpenComputers-MC1.12.2-1.7.7+5413028.jar
		* opencomputersapi|driver|item (7.0.0-alpha) from OpenComputers-MC1.12.2-1.7.7+5413028.jar
		* opencomputersapi|event (7.0.0-alpha) from OpenComputers-MC1.12.2-1.7.7+5413028.jar
		* opencomputersapi|filesystem (7.0.0-alpha) from OpenComputers-MC1.12.2-1.7.7+5413028.jar
		* opencomputersapi|internal (7.0.0-alpha) from OpenComputers-MC1.12.2-1.7.7+5413028.jar
		* opencomputersapi|machine (7.0.0-alpha) from OpenComputers-MC1.12.2-1.7.7+5413028.jar
		* opencomputersapi|manual (7.0.0-alpha) from OpenComputers-MC1.12.2-1.7.7+5413028.jar
		* opencomputersapi|network (7.0.0-alpha) from OpenComputers-MC1.12.2-1.7.7+5413028.jar
		* opencomputersapi|prefab (7.0.0-alpha) from OpenComputers-MC1.12.2-1.7.7+5413028.jar
		* PatchouliAPI (6) from Patchouli-1.0-23.6.jar
		* PneumaticCraftApi (1.1) from pneumaticcraft-repressurized-1.12.2-0.11.15-398.jar
		* projecteapi (1.12.2-1.2.0) from ProjectE-1.12.2-PE1.4.1.jar
		* projectred|api (2.1) from ProjectRed-1.12.2-4.9.4.120-Base.jar
		* QuarkAPI (4) from Quark-r1.6-179.jar
		* reborncoreAPI (3.19.5) from RebornCore-1.12.2-3.19.5-universal.jar
		* reborncoreAPI|Power (3.19.5) from RebornCore-1.12.2-3.19.5-universal.jar
		* reborncoreAPI|Recipe (3.19.5) from RebornCore-1.12.2-3.19.5-universal.jar
		* reborncoreAPI|Tile (3.19.5) from RebornCore-1.12.2-3.19.5-universal.jar
		* redstonefluxapi (2.1.1) from RedstoneFlux-1.12-2.1.1.1-universal.jar
		* StorageDrawersAPI (2.1.0) from StorageDrawers-1.12.2-5.4.2.jar
		* StorageDrawersAPI|event (2.1.0) from StorageDrawers-1.12.2-5.4.2.jar
		* StorageDrawersAPI|registry (2.1.0) from StorageDrawers-1.12.2-5.4.2.jar
		* StorageDrawersAPI|render (2.1.0) from StorageDrawers-1.12.2-5.4.2.jar
		* StorageDrawersAPI|storage (2.1.0) from StorageDrawers-1.12.2-5.4.2.jar
		* StorageDrawersAPI|storage-attribute (2.1.0) from StorageDrawers-1.12.2-5.4.2.jar
		* SuperScript (1.8.369) from BiomeTweaker-1.12.2-3.2.369.jar
		* SuperScript|script (1.8.369) from BiomeTweaker-1.12.2-3.2.369.jar
		* SuperScript|script|command (1.8.369) from BiomeTweaker-1.12.2-3.2.369.jar
		* SuperScript|script|object (1.8.369) from BiomeTweaker-1.12.2-3.2.369.jar
		* SuperScript|util (1.8.369) from BiomeTweaker-1.12.2-3.2.369.jar
		* team_reborn|Praescriptum (3.19.5) from RebornCore-1.12.2-3.19.5-universal.jar
		* tombstone-api (1.4.1) from tombstone-4.5.7-1.12.2.jar
		* tombstone-api-capability (1.4.1) from tombstone-4.5.7-1.12.2.jar
		* tombstone-api-event (1.4.1) from tombstone-4.5.7-1.12.2.jar
		* tombstone-api-magic (1.4.1) from tombstone-4.5.7-1.12.2.jar
		* tombstone-api-recipe (1.4.1) from tombstone-4.5.7-1.12.2.jar
		* WailaAPI (1.3) from Hwyla-1.8.26-B41_1.12.2.jar
		* wct|api (1.1) from WirelessCraftingTerminal-1.12.2-3.12.97.jar
		* wit|api (1.0.2) from WirelessInterfaceTerminal-1.12.2-1.0.2.jar
		* zerocore|API|multiblock (1.10.2-0.0.2) from zerocore-1.12.2-0.1.2.9.jar
		* zerocore|API|multiblock|rectangular (1.10.2-0.0.2) from zerocore-1.12.2-0.1.2.9.jar
		* zerocore|API|multiblock|tier (1.10.2-0.0.2) from zerocore-1.12.2-0.1.2.9.jar
		* zerocore|API|multiblock|validation (1.10.2-0.0.2) from zerocore-1.12.2-0.1.2.9.jar
	Extended Crafting: Nomifactory Edition: You are using a fork of Extended Crafting created for the Nomifactory modpack.
If the error above is a NoSuchFieldError or a NoSuchMethodError relating to
com.blakebr0.extendedcrafting,
then please report to https://github.com/Nomifactory/ExtendedCrafting/issues
with this crash report.
Otherwise, you can ignore this message.
	Patchouli open book context: n/a
	RebornCore: 
		Plugin Engine: 0
		RebornCore Version: 3.19.5
		Runtime Debofucsation 1
		Invalid fingerprint detected for RebornCore!
		RenderEngine: 0
	AE2 Integration: IC2:OFF, GTCE:OFF, RC:OFF, MFR:OFF, Waila:ON, InvTweaks:ON, JEI:ON, Mekanism:ON, OpenComputers:ON, THE_ONE_PROBE:OFF, TESLA:ON, CRAFTTWEAKER:ON
	Launched Version: forge-14.23.5.2860
	LWJGL: 2.9.4
	OpenGL: NVIDIA GeForce GTX 1070/PCIe/SSE2 GL version 4.6.0 NVIDIA 516.94, NVIDIA Corporation
	GL Caps: Using GL 1.3 multitexturing.
Using GL 1.3 texture combiners.
Using framebuffer objects because OpenGL 3.0 is supported and separate blending is supported.
Shaders are available because OpenGL 2.1 is supported.
VBOs are available because OpenGL 1.5 is supported.

	Using VBOs: No
	Is Modded: Definitely; Client brand changed to 'fml,forge'
	Type: Client (map_client.txt)
	Resource Packs: 
	Current Language: English (US)
	Profiler Position: N/A (disabled)
	CPU: 12x Intel(R) Core(TM) i7-8700 CPU @ 3.20GHz
