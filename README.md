# crash-log-nv-4.27


Yvileapsis' Cobb's AAAAAAA IT CRASHED Tweaks version 5.12 at 2025-04-27 22:49:32.5386306
If this file is empty, then your game didn't crash or something went so wrong even crash logger was useless! :snig:
Topmost stack module is NOT ALWAYS the crash reason! Exercise caution when speculating!
, pleas
When asking for helpe send the whole log file!

--------------------------------------------------------------------------------

Playtime: 00:00:39.1349922

Exception: EXCEPTION_ACCESS_VIOLATION (C0000005)

Thread: [FNV] Main

Calltrace:
   ebp     |              Function Address             |              Function Name               | Source
0x0019F898 |                    FalloutNV (0x008D6F30) |                                          |
0x0019F91C |                    FalloutNV (0x009EAB1E) |                                          |
0x0019F930 |                    FalloutNV (0x009DC5C0) |                                          |
0x0019F970 |                    FalloutNV (0x009DC2E4) |                                          |
0x0019FA00 |                    FalloutNV (0x008B336A) |                                          |
0x0019FA6C |                    FalloutNV (0x00886580) |                                          |
0x0019FA98 |           nvse_stewie_tweaks (0x10028220) | Process::ProcessManager__UpdateLowActors_UpdateProcessLists+0x140 | C:\Bethesda Modding\New Vegas\NV-Stewie-Tweaks\code\Features\Inlines\Process.cpp:228
0x0019FAD0 |                    FalloutNV (0x0096DA4D) |                                          |
0x0019FADC |                    FalloutNV (0x0086F90A) |                                          |
0x0019FAE8 |                    FalloutNV (0x008705E7) |                                          |
0x0019FB40 |                    FalloutNV (0x0086EDF5) |                                          |
0x0019FEC4 |                    FalloutNV (0x0086B3E8) |                                          |
0x0019FEE4 |            nvse_steam_loader (0x100021C4) |                                          |
0x0019FF74 |                    FalloutNV (0x00ECC470) |                                          |
0x0019FF84 |                     KERNEL32 (0x10015D49) | BaseThreadInitThunk+0x19                 |
0x0019FFDC |                        ntdll (0x1006CF0B) | RtlInitializeExceptionChain+0x6B         |
0x0019FFEC |                        ntdll (0x1006CE91) | RtlGetAppContainerNamedObjectPath+0x231  |

Registry:
REG |   Value    | DEREFERENCE INFO
eax | 0x00000001 | 
ebp | 0x0019F898 | 
ebx | 0x00000388 | 
ecx | 0x00000000 | 
edi | 0x3B06A1E0 | 0x01086A6C ==> Class: Character: ID: 00164251 ()
Plugin: "FalloutNV.esm"
Last modified by: "brayduck_classic.esp"
BaseForm: ID: FF001805 (Temp NPC)

edx | 0x0019F884 | 
eip | 0x008D6F30 | 
esi | 0x00000003 | 
esp | 0x0019F854 | 

Stack:
  # |   Value    | DEREFERENCE INFO
  0 | 0x009EAF09 | 
  1 | 0x00000000 | 
  2 | 0x3B06A1E0 | 0x01086A6C ==> Class: Character: ID: 00164251 ()
Plugin: "FalloutNV.esm"
Last modified by: "brayduck_classic.esp"
BaseForm: ID: FF001805 (Temp NPC)

  3 | 0x00000001 | 
  4 | 0x0019F874 | 
  5 | 0x131DFD00 | 0x010929FC ==> Class: VirtualActorPathHandler: 
  6 | 0x4600D311 | 
  7 | 0x4675E9E4 | 
  8 | 0x44E05398 | 
 22 | 0x32049180 | 0x010886E4 ==> Class: LowProcess: ID: 00164251 ()
Plugin: "FalloutNV.esm"
Last modified by: "brayduck_classic.esp"
BaseForm: ID: FF001805 (Temp NPC)

 35 | 0x195DB504 | 0x0109223C ==> Class: ActorMover: ID: 00164251 ()
Plugin: "FalloutNV.esm"
Last modified by: "brayduck_classic.esp"
BaseForm: ID: FF001805 (Temp NPC)

 42 | 0x1B0E7674 | 0x0104A2F4 ==> Class: TESNPC: ID: FF001805 (Temp NPC)

 4B | 0x3B39A000 | 0x01086A6C ==> Class: Character: ID: 1C01DE17 ()
Plugin: "Freeside Nightlife Expansion 1.0.esp"
BaseForm:
ID: 1C01DE13 (FNEHNDancer03)
Plugin: "Freeside Nightlife Expansion 1.0.esp"

 55 | 0x2C02D9C0 | 0x01037094 ==> Class: Script: ID: 00129112 (VStreetFluffNPCScript)
Plugin: "FalloutNV.esm"
Last modified by: "Simple Open Strip.esm"

 76 | 0x011E0E84 | 0x0108C0D0 ==> RTTI: NiTPrimitiveArray<class MobileObject *>
 A1 | 0x1807D6A4 | 0x01000000 ==> None: : 
 AC | 0x380026C0 | 0x0109CB9C ==> Class: NiCamera: "WorldRoot Camera"

 AF | 0x32002480 | 0x01083B5C ==> Class: SceneGraph: Name: "WorldRoot Node"

 B4 | 0x011F71A8 | 0x010A42B4 ==> Class: BSSystemUtility: 
 C4 | 0x0F40A060 | 0x1009D04C ==> RTTI:  myIDirect3DDevice9
 C7 | 0x0E000CB0 | 0x010472D0 ==> RTTI: BSSimpleArray<char const *,1024>
 DB | 0x777BAF1C | 0x000A7825 ==> String: "%x "
 E3 | 0x777BAF34 | 0x4C72644C ==> String: "LdrLoadDll"
 E7 | 0x777BAF04 | 0x6B6E696D ==> String: "minkernel\ldr\ldrapi.c"
 EB | 0x777BAF20 | 0x74617453 ==> String: "Status: 0x%08lx "
 F4 | 0x0019FDB4 | 0x794D5C73 ==> String: "s\My Games\FalloutNV\FalloutPrefs.ini"
 F8 | 0x0047005C | 0x01019A1C ==> RTTI: NiTPrimitiveArray<class TESObjectCELL *>

--------------------------------------------------------------------------------

Device:
OS:  "Windows 11 Home - 26100 (24H2)"
CPU: "13th Gen Intel(R) Core(TM) i5-13420H"
GPU: "NVIDIA GeForce RTX 4050 Laptop GPU"
RAM: "16.00 GB"

--------------------------------------------------------------------------------

Process' Memory:
Physical Usage: 866.79 MiB /  15.71 GiB (5.39%)
Virtual  Usage:   1.73 GiB /   4.00 GiB (43.32%)

Graphics Memory:
Budget Usage:     1.00 GiB /   5.03 GiB (19.92%)

Game's Heaps:
Default Heap    	 158.29 MiB / 200.00 MiB (79.15%)	  (18070000 - 24870000)
Static Heap     	 648.78 KiB /   1.51 MiB (41.86%)	  (07730020 - 078B3820)
File Heap       	   2.85 MiB /  64.00 MiB (4.46%)	  (078C0000 - 0B8C0000)

Game's Total Memory:
Total Heap Memory: 161.78 MiB / 265.51 MiB (60.93%)
Total Pool Memory:  99.24 MiB / 132.00 MiB (75.18%)
Total Memory:      261.01 MiB / 397.51 MiB (65.66%)

WARNING: NVTF.ini has bModifyDirectXBehavior=1 but bUseDefaultPoolForTextures=0! This will cause high memory usage!
         See https://performance.moddinglinked.com/falloutnv.html#NVTF on how to resolve this issue.

--------------------------------------------------------------------------------

Mods:
  # |                                       Mod                                        |                            Author                           
 00 | FalloutNV.esm                                                                    | ipely                                                       
 01 | DeadMoney.esm                                                                    | jfader                                                      
 02 | HonestHearts.esm                                                                 | jfader                                                      
 03 | OldWorldBlues.esm                                                                | jfader                                                      
 04 | LonesomeRoad.esm                                                                 | jfader                                                      
 05 | GunRunnersArsenal.esm                                                            | jfader                                                      
 06 | Fallout3.esm                                                                     | ipely                                                       
 07 | Anchorage.esm                                                                    | jduvall                                                     
 08 | ThePitt.esm                                                                      | jduvall                                                     
 09 | BrokenSteel.esm                                                                  | bchapin                                                     
 0A | PointLookout.esm                                                                 | jburgess                                                    
 0B | Zeta.esm                                                                         | ipely                                                       
 0C | CaravanPack.esm                                                                  | jfader                                                      
 0D | ClassicPack.esm                                                                  | jfader                                                      
 0E | MercenaryPack.esm                                                                | jfader                                                      
 0F | TribalPack.esm                                                                   | jfader                                                      
 10 | TaleOfTwoWastelands.esm                                                          | Tale of Two Wastelands Team                                 
 11 | YUPTTW.esm                                                                       | Yukichigai - sandbox6 - miguick - Roy Batty - Kazopert      
 12 | Better Character Creation.esm                                                    |                                                             
 13 | Interior Lighting Overhaul - Core.esm                                            | Sarge198                                                    
 14 | Interior Lighting Overhaul - L38PS.esm                                           | Sarge198                                                    
 15 | Simple Open Strip.esm                                                            |                                                             
 16 | StripCinematicLighting.esp                                                       |                                                             
 17 | Securitrons On Alert.esm                                                         | Nehred                                                      
 18 | Functional Post Game Ending.esm                                                  | Kazopert                                                    
 19 | Functional Post Game Ending - TTW Patch.esm                                      |                                                             
 1A | ADOBE_ClassicAdobeSloan.esp                                                      | Diegonom                                                    
 1B | ELECTRO-CITY - Highways and Byways.esm                                           | MyGoodEye                                                   
 1C | Freeside Nightlife Expansion 1.0.esp                                             | Tommygunner321                                              
 1D | ELECTRO-CITY - CompletedWorkorders.esm                                           | MyGoodEye                                                   
 1E | ImmortalBoone.esp                                                                |                                                             
 1F | Companion Poison Heal.esp                                                        |                                                             
 20 | ArcadeAfterQuest.esp                                                             |                                                             
 21 | UnlimitedCompanions.esp                                                          |                                                             
 22 | rina_companions_useful.esp                                                       |                                                             
 23 | AfterglowNeonIllumination.esp                                                    |                                                             
 24 | ImmersiveFastTravelEncounters.esp                                                | Lime                                                        
 25 | rockbiter_AnimationSounds.esp                                                    |                                                             
 26 | brayduck_classic.esp                                                             | brayduck                                                    
 27 | Interior Lighting Overhaul - Ultimate Edition.esp                                | Sarge198                                                    
 28 | ILO - GS Shack.esp                                                               | Sarge198                                                    
 29 | ILO - Tale of Two Wastelands.esp                                                 | Sarge198                                                    
 2A | ILO - PipBoy Light.esp                                                           | Sarge198                                                    
 2B | 10YearPack.esp                                                                   |                                                             
 2C | Brightweight Strip Overhaul Open.esp                                             |                                                             
 2D | Titans of The New West.esp                                                       |                                                             
 2E | Enhanced Movement.esp                                                            |                                                             
 2F | The Mod Configuration Menu.esp                                                   | Pelinor                                                     
 30 | B42Bash.esp                                                                      |                                                             
 31 | B42Wristwatch.esp                                                                | JazzIsParis & Hitman47101 & Xilandro Axeuora                
 32 | Diagonal movement.esp                                                            | Xilandro Axeuora & JazzIsParis                              
 33 | DNWeathers.esp                                                                   | Scott Clam                                                  
 34 | JustDynamicCrosshair.esp                                                         | yvileapsis                                                  
 35 | JustHitMarker.esp                                                                | yvileapsis                                                  
 36 | JustLootMenu.esp                                                                 | yvileapsis                                                  
 37 | Fast V.A.T.S. and Kill Camera.esp                                                |                                                             
 38 | Companion Sandbox Mode.esp                                                       | Povuholo                                                    
 39 | Altitude.esp                                                                     |                                                             
 3A | NeutralWeathers_TTW.esp                                                          |                                                             
 3B | B42Inspect.esp                                                                   |                                                             
 3C | Lucky 38 Lights Redone.esp                                                       | Nehred                                                      
 3D | Atmospheric Lighting Tweaks.esp                                                  |                                                             
 3E | Windows of the Mojave v1.2.1.esp                                                 | Gisli                                                       
 3F | WMIMNV.esp                                                                       |                                                             
 40 | Test_Cigarette.esp                                                               | zzjay                                                       
 41 | CharacterKitRemake-Hair.esp                                                      |                                                             
 42 | CharacterKitRemakeHHandsFix.esp                                                  |                                                             
 43 | Vanilla UI Plus.esp                                                              | Axonis                                                      

Script Runners:
  # |                                     Filename                                    
 00 | gr_0KEYWORDS.txt                                                                
 01 | gr_AccurateStars.txt                                                            
 02 | gr_BetterGrass.txt                                                              
 03 | gr_idlevariety.txt                                                              
 04 | gr_LUMEN-LightMod.txt                                                           
 05 | gr_MCPipBoy2000.txt                                                             
 06 | gr_securitron_siren_restored.txt                                                
 07 | gr_tnw_titans.txt                                                               
 08 | gr_tnw_titans_1h_1ha.txt                                                        
 09 | gr_tnw_titans_1h_2hl.txt                                                        
 0A | ln_AimCollisionIndicator.txt                                                    
 0B | ln_B42Core.txt                                                                  
 0C | ln_B42Interact.txt                                                              
 0D | ln_B42Leaning.txt                                                               
 0E | ln_B42Loot.txt                                                                  
 0F | ln_B42PatternEditor.txt                                                         
 10 | ln_B42Recoil.txt                                                                
 11 | ln_B42RecVerCheck.txt                                                           
 12 | ln_DynaBoy.txt                                                                  
 13 | ln_DynaBoyVerCheck.txt                                                          
 14 | ln_ISControl.txt                                                                
 15 | ln_NotifySmoothly.txt                                                           
 16 | ln_tnw_titans.txt                                                               

--------------------------------------------------------------------------------

Loaded assets:
Textures:       1114
  <=128:  228
  <=256:  419
  <=512:  176
  <=1024: 201
  <=2048: 78
  <=4096: 9
  <=8192: 3
Models:         888
FaceGen Models: 28
Animations:     1695

--------------------------------------------------------------------------------

Module bases:
         Address         |                                   Module |              Version | Filepath
 0x037B0000 - 0x037DF000 |                                  AnhNVSE |                  131 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/AnhNVSE.dll
 0x0C9D0000 - 0x0CA73000 |                        BaseObjectSwapper |                    1 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/BaseObjectSwapper.dll
 0x0CAF0000 - 0x0CB10000 |                                      CUM |                    1 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/CUM.dll
 0x70EA0000 - 0x70EBA000 |                           ClimateControl |                    0 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/ClimateControl.dll
 0x70DF0000 - 0x70E10000 |                             CloudUpgrade |                    0 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/CloudUpgrade.dll
 0x0CA80000 - 0x0CAEF000 |                              CrashLogger |                  512 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/CrashLogger.dll
 0x0CB10000 - 0x0CB29000 |                      EngineOptimizations |                  100 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/EngineOptimizations.dll
 0x0CB40000 - 0x0CB49000 |                    Fallout Shader Loader |              Unknown | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/Fallout Shader Loader.dll
 0x0CBE0000 - 0x0CC0B000 |                  ImprovedLightingShaders |                    9 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/ImprovedLightingShaders.dll
 0x0CDD0000 - 0x0CE02000 |                                      MCM |                    1 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/MCM.dll
 0x0CE80000 - 0x0CE91000 |                            MoonlightNVSE |                  200 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/MoonlightNVSE.dll
 0x0CF60000 - 0x0CF85000 |                      NVSE_EnhancedCamera |              Unknown | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/NVSE_EnhancedCamera.dll
 0x0CF90000 - 0x0CF9C000 |                                     NVTF |                   10 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/NVTF.dll
 0x0D600000 - 0x0D746000 |                              ShowOffNVSE |                  180 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/ShowOffNVSE.dll
 0x0DB70000 - 0x0DB89000 |                               VATSLagFix |              Unknown | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/VATSLagFix.dll
 0x0CB60000 - 0x0CBC9000 |                         improved_console |                    3 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/improved_console.dll
 0x0CC20000 - 0x0CCA0000 |                                 jip_nvse |                 5730 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/jip_nvse.dll
 0x0CCB0000 - 0x0CD0D000 |                             johnnyguitar |                  515 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/johnnyguitar.dll
 0x0CD20000 - 0x0CDB7000 |                                    kNVSE |                   37 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/kNVSE.dll
 0x0CE60000 - 0x0CE67000 |                                      mlf |                    3 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/mlf.dll
 0x0CEF0000 - 0x0CF58000 |                   nvse_console_clipboard |                    2 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/nvse_console_clipboard.dll
 0x0D500000 - 0x0D5FB000 |                       nvse_stewie_tweaks |                  941 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/nvse_stewie_tweaks.dll
 0x0D960000 - 0x0DA8E000 |                                  supNVSE |                  855 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/supNVSE.dll
 0x0DAA0000 - 0x0DAB0000 |                                 ttw_nvse |                  333 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/ttw_nvse.dll
 0x0DAC0000 - 0x0DACB000 |                             ui_organizer |                  230 | C:/Games/Steam/steamapps/common/Fallout New Vegas/Data/NVSE/Plugins/ui_organizer.dll
 0x00400000 - 0x0147B000 |                                FalloutNV |            1.4.0.525 | C:/Games/Steam/steamapps/common/Fallout New Vegas/FalloutNV.exe
 0x18000000 - 0x18068000 |                                  binkw32 |              1.7.3.0 | C:/Games/Steam/steamapps/common/Fallout New Vegas/binkw32.dll
 0x10000000 - 0x108F3000 |                                     d3d9 |              1.0.0.1 | C:/Games/Steam/steamapps/common/Fallout New Vegas/d3d9.dll
 0x01C70000 - 0x01DA3000 |                                libvorbis |              1.2.0.0 | C:/Games/Steam/steamapps/common/Fallout New Vegas/libvorbis.dll
 0x01C40000 - 0x01C5E000 |                            libvorbisfile |              1.2.0.0 | C:/Games/Steam/steamapps/common/Fallout New Vegas/libvorbisfile.dll
 0x0C840000 - 0x0C9CC000 |                                 nvse_1_4 |             0.6.3.10 | C:/Games/Steam/steamapps/common/Fallout New Vegas/nvse_1_4.dll
 0x70F10000 - 0x70F40000 |                        nvse_steam_loader |             0.6.3.10 | C:/Games/Steam/steamapps/common/Fallout New Vegas/nvse_steam_loader.dll
 0x3B400000 - 0x3B41D000 |                                steam_api |            7.9.87.40 | C:/Games/Steam/steamapps/common/Fallout New Vegas/steam_api.dll
 0x58A60000 - 0x58BE7000 |                                usvfs_x86 |              0.5.6.1 | C:/Modding/MO2/usvfs_x86.dll
 0x64E30000 - 0x6539F000 |                               MessageBus |       1.22.2758.1620 | C:/Program Files (x86)/NVIDIA Corporation/NvContainer/MessageBus.dll
 0x70D80000 - 0x70DA1000 |                               CSERHelper |             4.50.0.0 | C:/Program Files (x86)/Steam/CSERHelper.dll
 0x58900000 - 0x58A58000 |                      GameOverlayRenderer |            9.65.7.86 | C:/Program Files (x86)/Steam/GameOverlayRenderer.dll
 0x709B0000 - 0x70AB2000 |                                    steam |              Unknown | C:/Program Files (x86)/Steam/steam.dll
 0x5ACD0000 - 0x5C092000 |                              steamclient |            9.65.7.86 | C:/Program Files (x86)/Steam/steamclient.dll
 0x637F0000 - 0x6388C000 |                                  tier0_s |            9.65.7.86 | C:/Program Files (x86)/Steam/tier0_s.dll
 0x63750000 - 0x637E1000 |                                vstdlib_s |            9.65.7.86 | C:/Program Files (x86)/Steam/vstdlib_s.dll
 0x35C70000 - 0x35E50000 |                             nvse_dbghelp |      10.0.26100.3037 | C:/Users/*****/AppData/Local/Temp/nvse_dbghelp.dll
 0x5A9E0000 - 0x5AB54000 |                                 AUDIOSES |       6.2.26100.3624 | C:/Windows/SYSTEM32/AUDIOSES.DLL
 0x743B0000 - 0x743FA000 |                                 CFGMGR32 |       6.2.26100.3624 | C:/Windows/SYSTEM32/CFGMGR32.dll
 0x6F650000 - 0x6F65B000 |                                CRYPTBASE |       6.2.26100.2894 | C:/Windows/SYSTEM32/CRYPTBASE.DLL
 0x69130000 - 0x6916C000 |                             ControlLib32 |            1.0.200.0 | C:/Windows/SYSTEM32/ControlLib32.dll
 0x68FC0000 - 0x6909C000 |                            CoreMessaging |       6.2.26100.3624 | C:/Windows/SYSTEM32/CoreMessaging.dll
 0x58550000 - 0x587E2000 |                         CoreUIComponents |       6.2.26100.3624 | C:/Windows/SYSTEM32/CoreUIComponents.dll
 0x6FA20000 - 0x6FA44000 |                                   DEVOBJ |          6.2.26100.1 | C:/Windows/SYSTEM32/DEVOBJ.dll
 0x64B30000 - 0x64B68000 |                                  DINPUT8 |       6.2.26100.1591 | C:/Windows/SYSTEM32/DINPUT8.dll
 0x61300000 - 0x61376000 |                                   DSOUND |       6.2.26100.3624 | C:/Windows/SYSTEM32/DSOUND.dll
 0x707F0000 - 0x707FB000 |                                      HID |          6.2.26100.1 | C:/Windows/SYSTEM32/HID.DLL
 0x70840000 - 0x70867000 |                                 IPHLPAPI |       6.2.26100.3624 | C:/Windows/SYSTEM32/IPHLPAPI.DLL
 0x612B0000 - 0x612CA000 |                                  MSACM32 |       6.2.26100.1882 | C:/Windows/SYSTEM32/MSACM32.DLL
 0x70E30000 - 0x70E9D000 |                                 MSVCP140 |        14.42.34438.0 | C:/Windows/SYSTEM32/MSVCP140.dll
 0x71040000 - 0x71093000 |                                  MSWSOCK |       6.2.26100.3624 | C:/Windows/SYSTEM32/MSWSOCK.dll
 0x70990000 - 0x709A2000 |               Microsoft.Internal.WarpPal |              Unknown | C:/Windows/SYSTEM32/Microsoft.Internal.WarpPal.dll
 0x7BEA0000 - 0x7BED5000 |                                  RTWorkQ |       6.2.26100.3624 | C:/Windows/SYSTEM32/RTWorkQ.DLL
 0x5AC30000 - 0x5ACCA000 |                              ResampleDmo |          6.2.26100.1 | C:/Windows/SYSTEM32/ResampleDmo.DLL
 0x6F7E0000 - 0x6F7EA000 |                                  Secur32 |          6.2.26100.1 | C:/Windows/SYSTEM32/Secur32.dll
 0x71520000 - 0x7154B000 |                                  SspiCli |       6.2.26100.3775 | C:/Windows/SYSTEM32/SspiCli.dll
 0x50120000 - 0x501BE000 |                              TextShaping |       6.2.26100.3624 | C:/Windows/SYSTEM32/TextShaping.dll
 0x742B0000 - 0x742BE000 |                                    UMPDC |       6.2.26100.1301 | C:/Windows/SYSTEM32/UMPDC.dll
 0x70E10000 - 0x70E25000 |                             VCRUNTIME140 |        14.42.34438.0 | C:/Windows/SYSTEM32/VCRUNTIME140.dll
 0x6E0B0000 - 0x6E2CB000 |                                  WININET |      11.0.26100.3624 | C:/Windows/SYSTEM32/WININET.dll
 0x74400000 - 0x74433000 |                                    WINMM |       6.2.26100.3624 | C:/Windows/SYSTEM32/WINMM.dll
 0x71A70000 - 0x71A78000 |                                  WSOCK32 |          6.2.26100.1 | C:/Windows/SYSTEM32/WSOCK32.dll
 0x77E10000 - 0x77FEE000 |                            WindowsCodecs |       6.2.26100.3624 | C:/Windows/SYSTEM32/WindowsCodecs.dll
 0x016C0000 - 0x016D6000 |                                XINPUT1_3 |           9.18.944.0 | C:/Windows/SYSTEM32/XINPUT1_3.dll
 0x662C0000 - 0x662C7000 |                              XINPUT9_1_0 |          6.2.26100.1 | C:/Windows/SYSTEM32/XINPUT9_1_0.dll
 0x70F90000 - 0x7103C000 |                                  apphelp |       6.2.26100.3624 | C:/Windows/SYSTEM32/apphelp.dll
 0x50000000 - 0x50009000 |                                     avrt |          6.2.26100.1 | C:/Windows/SYSTEM32/avrt.dll
 0x6FD60000 - 0x6FD7A000 |                                   bcrypt |       6.2.26100.3037 | C:/Windows/SYSTEM32/bcrypt.dll
 0x6FCA0000 - 0x6FCCB000 |                                 cryptnet |       6.2.26100.3624 | C:/Windows/SYSTEM32/cryptnet.dll
 0x59250000 - 0x59445000 |                                    d3d11 |       6.2.26100.3624 | C:/Windows/SYSTEM32/d3d11.dll
 0x58BF0000 - 0x58FB8000 |                                 d3dx9_38 |        9.23.949.2378 | C:/Windows/SYSTEM32/d3dx9_38.dll
 0x5A020000 - 0x5A21F000 |                                 d3dx9_43 |        9.29.952.3111 | C:/Windows/SYSTEM32/d3dx9_43.dll
 0x70DB0000 - 0x70DDE000 |                                  dbgcore |       6.2.26100.3624 | C:/Windows/SYSTEM32/dbgcore.DLL
 0x6FA50000 - 0x6FC30000 |                                  dbghelp |       6.2.26100.3037 | C:/Windows/SYSTEM32/dbghelp.dll
 0x77A40000 - 0x77BD5000 |                                    dcomp |       6.2.26100.3775 | C:/Windows/SYSTEM32/dcomp.dll
 0x6F800000 - 0x6F81D000 |                                 dhcpcsvc |       6.2.26100.3624 | C:/Windows/SYSTEM32/dhcpcsvc.DLL
 0x6E2D0000 - 0x6E31D000 |                    directxdatabasehelper |       6.2.26100.3624 | C:/Windows/SYSTEM32/directxdatabasehelper.dll
 0x69850000 - 0x69979000 |                                 drvstore |       6.2.26100.3624 | C:/Windows/SYSTEM32/drvstore.dll
 0x73B10000 - 0x73B3B000 |                                   dwmapi |       6.2.26100.3775 | C:/Windows/SYSTEM32/dwmapi.dll
 0x6E350000 - 0x6E389000 |                                   dxcore |       6.2.26100.3624 | C:/Windows/SYSTEM32/dxcore.dll
 0x69750000 - 0x6984A000 |                                     dxgi |       6.2.26100.3624 | C:/Windows/SYSTEM32/dxgi.dll
 0x6FCD0000 - 0x6FCF0000 |                                    gpapi |       6.2.26100.1882 | C:/Windows/SYSTEM32/gpapi.dll
 0x70980000 - 0x7098B000 |                                 imaadp32 |          6.2.26100.1 | C:/Windows/SYSTEM32/imaadp32.acm
 0x694B0000 - 0x6961F000 |                                inputhost |       6.2.26100.3624 | C:/Windows/SYSTEM32/inputhost.dll
 0x74C10000 - 0x74C24000 |                           kernel.appcore |       6.2.26100.1591 | C:/Windows/SYSTEM32/kernel.appcore.dll
 0x79900000 - 0x79AA4000 |                                   mfplat |       6.2.26100.3624 | C:/Windows/SYSTEM32/mfplat.DLL
 0x5A9D0000 - 0x5A9D8000 |                                  midimap |       6.2.26100.1882 | C:/Windows/SYSTEM32/midimap.dll
 0x64520000 - 0x6452B000 |                                  msacm32 |       6.2.26100.1882 | C:/Windows/SYSTEM32/msacm32.drv
 0x64510000 - 0x6451A000 |                                  msadp32 |          6.2.26100.1 | C:/Windows/SYSTEM32/msadp32.acm
 0x70960000 - 0x7096E000 |                                   msasn1 |       6.2.26100.2894 | C:/Windows/SYSTEM32/msasn1.dll
 0x5A4D0000 - 0x5A576000 |                                    mscms |       6.2.26100.3624 | C:/Windows/SYSTEM32/mscms.dll
 0x65F60000 - 0x65F69000 |                                    msdmo |          6.2.26100.1 | C:/Windows/SYSTEM32/msdmo.dll
 0x64500000 - 0x64508000 |                                   msg711 |          6.2.26100.1 | C:/Windows/SYSTEM32/msg711.acm
 0x584F0000 - 0x584FC000 |                                  msgsm32 |       6.2.26100.1882 | C:/Windows/SYSTEM32/msgsm32.acm
 0x777B0000 - 0x7796A000 |                                    ntdll |       6.2.26100.3775 | C:/Windows/SYSTEM32/ntdll.dll
 0x6E320000 - 0x6E349000 |                                  ntmarta |          6.2.26100.1 | C:/Windows/SYSTEM32/ntmarta.dll
 0x63D90000 - 0x643A5000 |                                    nvapi |         32.0.15.6614 | C:/Windows/SYSTEM32/nvapi.dll
 0x75180000 - 0x751D5000 |                                 powrprof |       6.2.26100.3624 | C:/Windows/SYSTEM32/powrprof.dll
 0x71A80000 - 0x71AA2000 |                                  profapi |       6.2.26100.3624 | C:/Windows/SYSTEM32/profapi.dll
 0x70D60000 - 0x70D70000 |                     resourcepolicyclient |          6.2.26100.1 | C:/Windows/SYSTEM32/resourcepolicyclient.dll
 0x0FEF0000 - 0x0FFF4000 |                       textinputframework |       6.2.26100.3624 | C:/Windows/SYSTEM32/textinputframework.dll
 0x6F630000 - 0x6F647000 |                                    usp10 |          6.2.26100.1 | C:/Windows/SYSTEM32/usp10.dll
 0x74C00000 - 0x74C08000 |                                  version |          6.2.26100.1 | C:/Windows/SYSTEM32/version.dll
 0x5AB60000 - 0x5AB9D000 |                                   wdmaud |       6.2.26100.1882 | C:/Windows/SYSTEM32/wdmaud.drv
 0x73BD0000 - 0x742A0000 |                          windows.storage |       6.2.26100.3624 | C:/Windows/SYSTEM32/windows.storage.dll
 0x612D0000 - 0x612EF000 |                                winmmbase |          6.2.26100.1 | C:/Windows/SYSTEM32/winmmbase.dll
 0x714A0000 - 0x714F0000 |                                     wldp |       6.2.26100.2894 | C:/Windows/SYSTEM32/wldp.dll
 0x77710000 - 0x7778E000 |                                 ADVAPI32 |       6.2.26100.3775 | C:/Windows/System32/ADVAPI32.dll
 0x753D0000 - 0x75489000 |                                 COMDLG32 |       6.2.26100.3624 | C:/Windows/System32/COMDLG32.dll
 0x76390000 - 0x76497000 |                                  CRYPT32 |       6.2.26100.3775 | C:/Windows/System32/CRYPT32.dll
 0x6FD40000 - 0x6FD55000 |                                  CRYPTSP |       6.2.26100.2454 | C:/Windows/System32/CRYPTSP.dll
 0x690A0000 - 0x69128000 |                        IntelControlLib32 |            1.0.200.0 | C:/Windows/System32/DriverStore/FileRepository/iigd_dch.inf_amd64_eb07181cd8456323/IntelControlLib32.dll
 0x5DC00000 - 0x61270000 |                                    igc32 |        31.0.101.5592 | C:/Windows/System32/DriverStore/FileRepository/iigd_dch.inf_amd64_eb07181cd8456323/igc32.dll
 0x69980000 - 0x6AD45000 |                            igd9trinity32 |        31.0.101.5592 | C:/Windows/System32/DriverStore/FileRepository/iigd_dch.inf_amd64_eb07181cd8456323/igd9trinity32.dll
 0x69170000 - 0x694A7000 |                                 igdgmm32 |        31.0.101.5592 | C:/Windows/System32/DriverStore/FileRepository/iigd_dch.inf_amd64_eb07181cd8456323/igdgmm32.dll
 0x661C0000 - 0x662BA000 |                                  igdml32 |        31.0.101.5592 | C:/Windows/System32/DriverStore/FileRepository/iigd_dch.inf_amd64_eb07181cd8456323/igdml32.dll
 0x6AD50000 - 0x6AFEE000 |                               igdumdim32 |        31.0.101.5592 | C:/Windows/System32/DriverStore/FileRepository/iigd_dch.inf_amd64_eb07181cd8456323/igdumdim32.dll
 0x501D0000 - 0x509B4000 |                               NvCamera32 |              7.1.0.0 | C:/Windows/System32/DriverStore/FileRepository/nvmi.inf_amd64_9a9d1548c06ce277/NvCamera/NvCamera32.dll
 0x78A90000 - 0x78DE6000 |                        d3dcompiler_47_32 |       6.3.9600.16384 | C:/Windows/System32/DriverStore/FileRepository/nvmi.inf_amd64_9a9d1548c06ce277/NvCamera/d3dcompiler_47_32.dll
 0x53FD0000 - 0x5601E000 |                                  nvd3dum |         32.0.15.6614 | C:/Windows/System32/DriverStore/FileRepository/nvmi.inf_amd64_9a9d1548c06ce277/nvd3dum.dll
 0x56020000 - 0x584C8000 |                              nvgpucomp32 |         32.0.15.6614 | C:/Windows/System32/DriverStore/FileRepository/nvmi.inf_amd64_9a9d1548c06ce277/nvgpucomp32.dll
 0x5A8F0000 - 0x5A98D000 |                                  nvldumd |         32.0.15.6614 | C:/Windows/System32/DriverStore/FileRepository/nvmi.inf_amd64_9a9d1548c06ce277/nvldumd.dll
 0x59F40000 - 0x5A01F000 |                                    nvppe |         32.0.15.6614 | C:/Windows/System32/DriverStore/FileRepository/nvmi.inf_amd64_9a9d1548c06ce277/nvppe.dll
 0x509C0000 - 0x53FCF000 |                                 nvwgf2um |         32.0.15.6614 | C:/Windows/System32/DriverStore/FileRepository/nvmi.inf_amd64_9a9d1548c06ce277/nvwgf2um.dll
 0x75C30000 - 0x75C52000 |                                    GDI32 |       6.2.26100.3775 | C:/Windows/System32/GDI32.dll
 0x77160000 - 0x77185000 |                                    IMM32 |       6.2.26100.3775 | C:/Windows/System32/IMM32.DLL
 0x76600000 - 0x766F0000 |                                 KERNEL32 |       6.2.26100.3775 | C:/Windows/System32/KERNEL32.DLL
 0x75490000 - 0x7573D000 |                               KERNELBASE |       6.2.26100.3775 | C:/Windows/System32/KERNELBASE.dll
 0x5ABA0000 - 0x5AC1E000 |                                 MMDevApi |       6.2.26100.3624 | C:/Windows/System32/MMDevApi.dll
 0x76030000 - 0x76148000 |                                    MSCTF |       6.2.26100.3624 | C:/Windows/System32/MSCTF.dll
 0x753B0000 - 0x753B7000 |                                      NSI |       6.2.26100.2894 | C:/Windows/System32/NSI.dll
 0x77190000 - 0x7722E000 |                                 OLEAUT32 |       6.2.26100.3624 | C:/Windows/System32/OLEAUT32.dll
 0x773C0000 - 0x77479000 |                                   RPCRT4 |       6.2.26100.3037 | C:/Windows/System32/RPCRT4.dll
 0x75740000 - 0x75B8F000 |                                 SETUPAPI |       6.2.26100.3624 | C:/Windows/System32/SETUPAPI.dll
 0x75E70000 - 0x75F3A000 |                                   SHCORE |       6.2.26100.3775 | C:/Windows/System32/SHCORE.dll
 0x769E0000 - 0x76FE9000 |                                  SHELL32 |       6.2.26100.3624 | C:/Windows/System32/SHELL32.dll
 0x76FF0000 - 0x77040000 |                                  SHLWAPI |       6.2.26100.3624 | C:/Windows/System32/SHLWAPI.dll
 0x761C0000 - 0x76388000 |                                   USER32 |       6.2.26100.3775 | C:/Windows/System32/USER32.dll
 0x58500000 - 0x58541000 |                                    WMASF |         12.0.26100.1 | C:/Windows/System32/WMASF.DLL
 0x79660000 - 0x79830000 |                                  WMVCore |      12.0.26100.1882 | C:/Windows/System32/WMVCore.DLL
 0x76150000 - 0x761B0000 |                                   WS2_32 |       6.2.26100.1882 | C:/Windows/System32/WS2_32.dll
 0x29A30000 - 0x29A89000 | Windows.Internal.Graphics.Display.DisplayColorManagement |       6.2.26100.3624 | C:/Windows/System32/Windows.Internal.Graphics.Display.DisplayColorManagement.dll
 0x50010000 - 0x5011D000 |                               Windows.UI |       6.2.26100.3624 | C:/Windows/System32/Windows.UI.dll
 0x75BA0000 - 0x75C09000 |                         bcryptPrimitives |       6.2.26100.3037 | C:/Windows/System32/bcryptPrimitives.dll
 0x10900000 - 0x10981000 |                                  clbcatq |  2001.12.10941.16384 | C:/Windows/System32/clbcatq.dll
 0x77480000 - 0x77704000 |                                  combase |       6.2.26100.3775 | C:/Windows/System32/combase.dll
 0x64A80000 - 0x64A9C000 |                                  devenum |       6.2.26100.1882 | C:/Windows/System32/devenum.dll
 0x75F40000 - 0x7602D000 |                                gdi32full |       6.2.26100.3775 | C:/Windows/System32/gdi32full.dll
 0x75C10000 - 0x75C2B000 |                                 imagehlp |          6.2.26100.1 | C:/Windows/System32/imagehlp.dll
 0x584D0000 - 0x584E6000 |                                 l3codeca |            1.9.0.401 | C:/Windows/System32/l3codeca.acm
 0x79BB0000 - 0x79CB8000 |                             mfperfhelper |          6.2.26100.1 | C:/Windows/System32/mfperfhelper.dll
 0x64990000 - 0x649A8000 |                                  mp3dmod |          6.2.26100.1 | C:/Windows/System32/mp3dmod.dll
 0x79B20000 - 0x79BA5000 |                              msmpeg2adec |          6.2.26100.1 | C:/Windows/System32/msmpeg2adec.dll
 0x75C60000 - 0x75CE5000 |                                msvcp_win |       6.2.26100.1882 | C:/Windows/System32/msvcp_win.dll
 0x76530000 - 0x765F7000 |                                   msvcrt |       7.0.26100.1882 | C:/Windows/System32/msvcrt.dll
 0x76700000 - 0x76852000 |                                    ole32 |       6.2.26100.3624 | C:/Windows/System32/ole32.dll
 0x773B0000 - 0x773B6000 |                                    psapi |          6.2.26100.1 | C:/Windows/System32/psapi.dll
 0x5A8C0000 - 0x5A8E4000 |                                     qasf |         12.0.26100.1 | C:/Windows/System32/qasf.dll
 0x794B0000 - 0x79653000 |                                   quartz |       6.2.26100.1882 | C:/Windows/System32/quartz.dll
 0x764A0000 - 0x76523000 |                                  sechost |       6.2.26100.3775 | C:/Windows/System32/sechost.dll
 0x76860000 - 0x76970000 |                                 ucrtbase |       6.2.26100.3624 | C:/Windows/System32/ucrtbase.dll
 0x75390000 - 0x753AA000 |                                   win32u |       6.2.26100.3775 | C:/Windows/System32/win32u.dll
 0x770F0000 - 0x77156000 |                                 wintrust |       6.2.26100.3624 | C:/Windows/System32/wintrust.dll
 0x772B0000 - 0x773A9000 |                                 wintypes |       6.2.26100.2894 | C:/Windows/System32/wintypes.dll
 0x6FD80000 - 0x6FE11000 |                                 COMCTL32 |      5.82.26100.3624 | C:/Windows/WinSxS/x86_microsoft.windows.common-controls_6595b64144ccf1df_5.82.26100.3624_none_cf9f0f668ea64cb7/COMCTL32.dll
 0x74C30000 - 0x74DA2000 |                                  gdiplus |       6.2.26100.3624 | C:/Windows/WinSxS/x86_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.26100.3624_none_b6a0931f524301f8/gdiplus.dll
 0x6AFF0000 - 0x6B16D000 |                                     d3d9 |       6.2.26100.3624 | C:/Windows/system32/d3d9.dll
 0x77BE0000 - 0x77E0A000 |                                  nvspcap |           3.27.0.114 | C:/Windows/system32/nvspcap.dll
 0x6FD00000 - 0x6FD33000 |                                   rsaenh |       6.2.26100.3624 | C:/Windows/system32/rsaenh.dll
 0x73B40000 - 0x73BC2000 |                                  uxtheme |       6.2.26100.3624 | C:/Windows/system32/uxtheme.dll

Total memory allocated to modules: 383.32 MiB

GAME CRASHED AT INSTRUCTION Base+0x004D6F30 IN MODULE: C:\Games\Steam\steamapps\common\Fallout New Vegas\FalloutNV.exe
Please note that this does not automatically mean that that module is responsible. It may have been supplied bad data or
program state as the result of an issue in the base game or a different DLL.

--------------------------------------------------------------------------------

Install: C:/Games/Steam/steamapps/common/Fallout New Vegas/

Processed in 975 ms, printed in 0 ms

