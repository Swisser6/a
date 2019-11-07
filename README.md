Help Minecraft crash 
---- Minecraft Crash Report ----
// Hi. I'm Minecraft, and I'm a crashaholic.

Time: 07-11-2019 14:07
Description: Initializing game

java.lang.NoSuchMethodError: net.minecraft.client.renderer.texture.TextureMap.<init>(ILjava/lang/String;Z)V
	at net.minecraft.client.Minecraft.func_71384_a(Minecraft.java:540)
	at net.minecraft.client.Minecraft.func_99999_d(Minecraft.java:878)
	at net.minecraft.client.main.Main.main(SourceFile:148)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:497)
	at net.minecraft.launchwrapper.Launch.launch(Launch.java:135)
	at net.minecraft.launchwrapper.Launch.main(Launch.java:28)


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Stacktrace:
	at net.minecraft.client.Minecraft.func_71384_a(Minecraft.java:540)

-- Initialization --
Details:
Stacktrace:
	at net.minecraft.client.Minecraft.func_99999_d(Minecraft.java:878)
	at net.minecraft.client.main.Main.main(SourceFile:148)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:497)
	at net.minecraft.launchwrapper.Launch.launch(Launch.java:135)
	at net.minecraft.launchwrapper.Launch.main(Launch.java:28)

-- System Details --
Details:
	Minecraft Version: 1.7.10
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 1.8.0_51, Oracle Corporation
	Java VM Version: Java HotSpot(TM) 64-Bit Server VM (mixed mode), Oracle Corporation
	Memory: 424124280 bytes (404 MB) / 939524096 bytes (896 MB) up to 2147483648 bytes (2048 MB)
	JVM Flags: 8 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xmx2G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
	AABB Pool Size: 0 (0 bytes; 0 MB) allocated, 0 (0 bytes; 0 MB) used
	IntCache: cache: 0, tcache: 0, allocated: 0, tallocated: 0
	FML: MCP v9.05 FML v7.10.99.99 Minecraft Forge 10.13.4.1558 Optifine OptiFine_1.7.10_HD_B4 49 mods loaded, 49 mods active
	States: 'U' = Unloaded 'L' = Loaded 'C' = Constructed 'H' = Pre-initialized 'I' = Initialized 'J' = Post-initialized 'A' = Available 'D' = Disabled 'E' = Errored
	UCH	mcp{9.05} [Minecraft Coder Pack] (minecraft.jar) 
	UCH	FML{7.10.99.99} [Forge Mod Loader] (forge-1.7.10-10.13.4.1558-1.7.10.jar) 
	UCH	Forge{10.13.4.1558} [Minecraft Forge] (forge-1.7.10-10.13.4.1558-1.7.10.jar) 
	UCH	CodeChickenCore{1.0.4.29} [CodeChicken Core] (minecraft.jar) 
	UCH	NotEnoughItems{1.0.3.74} [Not Enough Items] (NotEnoughItems-1.7.10-1.0.3.74-universal.jar) 
	UCH	modJ_StarMinerCore{0.9.8} [StarMinerCore] (minecraft.jar) 
	UCH	battlegear2{1.0.7.0} [Mine & Blade Battlegear 2 - Bullseye] (1.7.10-MB_Battlegear2-Bullseye-1.0.7.0.jar) 
	UCH	oresheepmod{v2.3} [Ore Sheep] (1.7.10-OreSheepMod-v2.3.jar) 
	UCH	zeldaswordskills{1.7.10-0.2.1} [Zelda Sword Skills] (1.7.10-zeldaswordskills-0.2.1.jar) 
	UCH	lucky{5.1.0} [Lucky Block] ([1-7-10]_Lucky_Block_v5-1-0.jar) 
	UCH	FLabsBF{4.3} [Better Furnaces] ([1.7.10]Better_Furnaces_V4.3.jar) 
	UCH	DamageIndicatorsMod{3.2.0} [Damage Indicators] ([1.7.10]DamageIndicatorsMod-3.2.0.jar) 
	UCH	Baubles{1.0.1.10} [Baubles] (Baubles-1.7.10-1.0.1.10.jar) 
	UCH	adventurebackpack{1.7.10-0.8b} [Adventure Backpack] (adventurebackpack-1.7.10-0.8b.jar) 
	UCH	betterstorage{0.12.0.124} [BetterStorage] (BetterStorage-1.7.10-0.12.0.124.jar) 
	UCH	BiblioCraft{1.9.2} [BiblioCraft] (BiblioCraft[v1.9.2][MC1.7.10].jar) 
	UCH	BiomesOPlenty{2.1.0} [Biomes O' Plenty] (BiomesOPlenty-1.7.10-2.1.0.1062-universal.jar) 
	UCH	BiblioWoodsBoP{1.9} [BiblioWoods Biomes O'Plenty Edition] (BiblioWoods[BiomesOPlenty][v1.9].jar) 
	UCH	Botania{r1.4-157} [Botania] (Botania r1.4-157.jar) 
	UCH	CarpentersBlocks{3.3.5} [Carpenter's Blocks] (Carpenter's Blocks v3.3.5 - MC 1.7.10.jar) 
	UCH	craftingpillars{1.6.0} [Crafting Pillars Mod] (CraftingPillars-1.7.x-1.6.1.jar) 
	UCH	Doca{1.7.4_2.2.7} [DogCatPlus] (Dog-Cat-Plus-Mod-1.7.10.jar) 
	UCH	ForgeMultipart{1.1.1.320} [Forge Multipart] (ForgeMultipart-1.7.10-1.1.1.320-universal.jar) 
	UCH	ExtraUtilities{1.2.1} [Extra Utilities] (extrautilities-1.2.1.jar) 
	UCH	farlanders{1.2b} [The Farlanders] (farlanders-1.7.10-v1.2b.jar) 
	UCH	iChunUtil{4.1.3} [iChunUtil] (iChunUtil-4.1.3.jar) 
	UCH	IronChest{6.0.41.729} [Iron Chest] (ironchest-1.7.10-6.0.41.729-universal.jar) 
	UCH	LotsOfFood{1.7.10} [Lots of Food] (Lots of Food-1.7.10 v6.jar) 
	UCH	mcheli{0.10.5} [MC Helicopter] (mcheli) 
	UCH	mm{1.2} [M&Ms] (MM-Mod-1.2.jar) 
	UCH	mobarmormod{1.4 Beta} [mobarmormod] (Mob Armor Mod V1.3-1.7.10.jar) 
	UCH	morehealth{6.0} [More Health Forge] (More-Health-Enhanced-Mod-1.7.10.zip) 
	UCH	Morph{0.9.1} [Morph] (Morph-Beta-0.9.1.jar) 
	UCH	cfm{3.4.7} [�9MrCrayfish's Furniture Mod] (MrCrayfishFurnitureModv3.4.7(1.7.10).jar) 
	UCH	OreSpawn{1.7.10.20.2} [OreSpawn] (orespawn-1.7.10-20.2(1).zip) 
	UCH	potatogun{1.1.2} [The Potatogun Mod] (Potato-Gun-Mod-1.7.10.jar) 
	UCH	radixcore{1.3.3} [RadixCore] (RadixCore-1.7.x-1.3.3-universal.jar) 
	UCH	RefinedRelocation{1.0.7d} [Refined Relocation] (RefinedRelocation-1.7.10-1.0.7d.jar) 
	UCH	rc{1.0} [Rollercoaster Mod] (Rollercoaster.jar) 
	UCH	secretroomsmod{4.7.1} [The SecretRoomsMod] (secretroomsmod-1.7.10-4.7.1.397.jar) 
	UCH	shit{1.3} [Poop Mod] (shit-1.3_1.7.10.jar) 
	UCH	SSR{Alpha 0.9a} [Soul Shards: Reborn] (Soul-Shards-Reborn-Mod-1.7.10.jar) 
	UCH	spiderqueen{1.2.2} [Spider Queen - Reborn] (SpiderQueenReborn-1.7.10-1.2.2-universal.jar) 
	UCH	modJ_StarMiner{0.9.8bf1} [Starminer Mod] (Starminer1710-0.9.8bf1.jar) 
	UCH	HeroSuits{1.7} [Hero Suits] (SuperHuman-Mod-1.7.10.jar) 
	UCH	kitchen{1.3.8} [The Kitchen Mod] (TheKitchenMod-1.3.8-1.7.2-10.jar) 
	UCH	sgs_treasure{2.5} [SGS Treasure!] (Treasure-1.7.10-2.5-BETA.jar) 
	UCH	McMultipart{1.1.1.320} [Minecraft Multipart Plugin] (ForgeMultipart-1.7.10-1.1.1.320-universal.jar) 
	UCH	ForgeMicroblock{1.1.1.320} [Forge Microblocks] (ForgeMultipart-1.7.10-1.1.1.320-universal.jar) 
	Launched Version: 1.7.10-Forge10.13.4.1558-1.7.10
	LWJGL: 2.9.1
	OpenGL: GeForce GTX 1060 3GB/PCIe/SSE2 GL version 4.6.0 NVIDIA 417.35, NVIDIA Corporation
	GL Caps: Using GL 1.3 multitexturing.
Using framebuffer objects because OpenGL 3.0 is supported and separate blending is supported.
Anisotropic filtering is supported and maximum anisotropy is 16.
Shaders are available because OpenGL 2.1 is supported.

	Is Modded: Definitely; Client brand changed to 'fml,forge'
	Type: Client (map_client.txt)
	Resource Packs: []
	Current Language: English (US)
	Profiler Position: N/A (disabled)
	Vec3 Pool Size: 0 (0 bytes; 0 MB) allocated, 0 (0 bytes; 0 MB) used
	Anisotropic Filtering: Off (1)
