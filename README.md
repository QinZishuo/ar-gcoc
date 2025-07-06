# ar-gcoc  
AMD Radeon™ Graphics card optimized configuration  
  
These profiles are for non-reference and select reference AMD Radeon™ graphics cards.  
Please click "Import Profile" in the upper column of the AMD Software - Performance - Tuning page to import the corresponding graphics card profile.  
  
WARNING: For public version graphics cards, please import the configuration of the corresponding public version graphics card. The configuration file with -P after the graphics card model is for public version, such as 5700XT-P-FPS.xml  
If you import a non-public version configuration into a public version graphics card, please restore the default settings immediately, otherwise it may cause a black screen, a flashing screen, a distorted screen, or even core damage.  
  
The meaning of the configuration file name, from top to bottom corresponds to the file name from left to right:  
1.==============================  
-P: Applicable to public version graphics cards, non-public version models omit this suffix.  
2.==============================  
-F:  fps      | Profile for FPS games. Stabilizes the frame rate by lowering some frequencies, usually by 0.5%~2.8%. Note that it does not work for some 3a games and may cause negative optimization.  
-3a: 3A game  | Applicable to 3a games, not applicable to online games like cs2, which may lead to negative optimization.  
-G:  game     | Balanced optimization for all games. Compared with -f, it will not reduce the frequency too much to ensure the frame rate stability. Compared with -3a, it will not optimize 3a games through too large a frequency space, but will try to ensure that both are optimized.  
-B:  balanced | Balanced profile. It does not limit the minimum frequency of the graphics card to achieve the highest gaming performance. Instead, it is as balanced as possible. It will not consume too much power. Instead, it optimizes both gaming and daily office work as much as possible. Note that the gaming performance of this profile is far inferior to that of -F and -3a. Therefore, gamers are advised to use -B and -F.  
3.==============================  
-OC: overclocking  
-UC: underclocking  
4.=============================  
-Dev:  Dev Version  | Dev version, the most unstable version. Use this version to report problems to developers and propose solutions if you have any. Once the fix is ​​complete, it will be converted to Beta version. This version file name usually carries the build date at the end.
-Beta: Beta Version | The test version after the Dev version is more stable than the Dev version, but not as stable as the official version.  
-Release: Releases  | The most stable version.  
Note that the suffix in each box above can appear at most once, and there can be at most 4 suffixes, corresponding to the file name from left to right from top to bottom.  
