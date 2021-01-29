{"blame":["\/usr\/lib\/libpackageinfo.dylib"],"app_name":"CrashReporter","timestamp":"2021-01-29 10:57:35.00 -0500","app_version":"","slice_uuid":"3d1c08c7-1c53-3ec0-bc24-c16a4b1caafe","adam_id":0,"build_version":"1.16.0","bundleID":"crash-reporter","share_with_app_devs":0,"is_first_party":1,"bug_type":"109","os_version":"iPhone OS 13.5 (17F75)","incident_id":"DF1CC0B2-8360-479D-B04B-6EDBCCEEA3DD","name":"CrashReporter","symbolicated":true}
Incident Identifier: DF1CC0B2-8360-479D-B04B-6EDBCCEEA3DD
CrashReporter Key:   19ef6b083c53ee5a8052c7ceae080e36dc4810c1
Hardware Model:      iPhone12,8
Process:             CrashReporter [3565]
Path:                /Applications/CrashReporter.app/CrashReporter
Identifier:          crash-reporter
Version:             1.16.0
Code Type:           ARM-64 (Native)
Role:                Foreground
Parent Process:      launchd [1]
Coalition:           crash-reporter [1761]


Date/Time:           2021-01-29 10:57:34.6246 -0500
Launch Time:         2021-01-29 10:57:31.4794 -0500
OS Version:          iPhone OS 13.5 (17F75)
Release Type:        User
Baseband Version:    1.06.00
Report Version:      104

Exception Type:  EXC_CRASH (SIGABRT)
Exception Codes: 0x0000000000000000, 0x0000000000000000
Exception Note:  EXC_CORPSE_NOTIFY
Triggered by Thread:  0

Last Exception Backtrace:
0       CoreFoundation                	0x1ad168300 0x1ad036000 + 0x132300
1       libobjc.A.dylib               	0x1ace7cc1c 0x1ace77000 + 0x5c1c
2       CoreFoundation                	0x1ad066a90 0x1ad036000 + 0x30a90
3       CoreFoundation                	0x1ad16ca60 0x1ad036000 + 0x136a60
4       CoreFoundation                	0x1ad16ed60 0x1ad036000 + 0x138d60
5     + libpackageinfo.dylib          	0x100947768 0x100928000 + 0x1f768
6     + libpackageinfo.dylib          	0x100946008 0x100928000 + 0x1e008
7       libobjc.A.dylib               	0x1ace78534 0x1ace77000 + 0x1534
8       libobjc.A.dylib               	0x1ace7e1a0 0x1ace77000 + 0x71a0
9       libobjc.A.dylib               	0x1ace7f630 0x1ace77000 + 0x8630
10      libobjc.A.dylib               	0x1ace8c624 0x1ace77000 + 0x15624
11      libobjc.A.dylib               	0x1ace78d60 0x1ace77000 + 0x1d60
12    + CrashReporter (*)             	0x100878430 0x100870000 + 0x8430	// -[BinaryImageCell configureWithObject:] + 0x344
13    + CrashReporter (*)             	0x1008832f0 0x100870000 + 0x132f0	// -[TableViewController tableView:cellForRowAtIndexPath:] + 0x150
14      UIKitCore                     	0x1b14b2b38 0x1b0842000 + 0xc70b38
15      UIKitCore                     	0x1b147fcc8 0x1b0842000 + 0xc3dcc8
16      UIKitCore                     	0x1b149cfe0 0x1b0842000 + 0xc5afe0
17      UIKitCore                     	0x1b1783284 0x1b0842000 + 0xf41284
18      QuartzCore                    	0x1b3dd2718 0x1b3c7a000 + 0x158718
19      QuartzCore                    	0x1b3dd2b58 0x1b3c7a000 + 0x158b58
20      QuartzCore                    	0x1b3de503c 0x1b3c7a000 + 0x16b03c
21      QuartzCore                    	0x1b3d2995c 0x1b3c7a000 + 0xaf95c
22      QuartzCore                    	0x1b3d544bc 0x1b3c7a000 + 0xda4bc
23      QuartzCore                    	0x1b3d550b4 0x1b3c7a000 + 0xdb0b4
24      CoreFoundation                	0x1ad0e2ee8 0x1ad036000 + 0xacee8
25      CoreFoundation                	0x1ad0ddb78 0x1ad036000 + 0xa7b78
26      CoreFoundation                	0x1ad0de018 0x1ad036000 + 0xa8018
27      CoreFoundation                	0x1ad0dd8f4 0x1ad036000 + 0xa78f4
28      GraphicsServices              	0x1b74f4604 0x1b74f1000 + 0x3604
29      UIKitCore                     	0x1b12b1358 0x1b0842000 + 0xa6f358
30    + CrashReporter (*)             	0x100884698 0x100870000 + 0x14698	// main + 0x54
31      libdyld.dylib                 	0x1acf592dc 0x1acf58000 + 0x12dc

Thread 0 name:  Dispatch queue: com.apple.main-thread
Thread 0 Crashed:
0       libsystem_kernel.dylib        	0x1acf4edf0 0x1acf28000 + 0x26df0
1       libsystem_pthread.dylib       	0x1ace6e930 0x1ace6c000 + 0x2930
2       libsystem_c.dylib             	0x1acdfcba4 0x1acd86000 + 0x76ba4
3       libc++abi.dylib               	0x1acf21f40 0x1acf12000 + 0xff40
4       libc++abi.dylib               	0x1acf138c8 0x1acf12000 + 0x18c8
5       libobjc.A.dylib               	0x1ace7cf0c 0x1ace77000 + 0x5f0c
6       libc++abi.dylib               	0x1acf213cc 0x1acf12000 + 0xf3cc
7       libc++abi.dylib               	0x1acf24154 0x1acf12000 + 0x12154
8       libobjc.A.dylib               	0x1ace7cde8 0x1ace77000 + 0x5de8
9       CoreFoundation                	0x1ad0dd964 0x1ad036000 + 0xa7964
10      GraphicsServices              	0x1b74f4604 0x1b74f1000 + 0x3604
11      UIKitCore                     	0x1b12b1358 0x1b0842000 + 0xa6f358
12    + CrashReporter (*)             	0x100884698 0x100870000 + 0x14698	// main + 0x54
13      libdyld.dylib                 	0x1acf592dc 0x1acf58000 + 0x12dc

Thread 1:
0       libsystem_pthread.dylib       	0x1ace759c0 0x1ace6c000 + 0x99c0

Thread 2:
0       libsystem_pthread.dylib       	0x1ace759c0 0x1ace6c000 + 0x99c0

Thread 3:
0       libsystem_pthread.dylib       	0x1ace759c0 0x1ace6c000 + 0x99c0

Thread 4 name:  com.apple.uikit.eventfetch-thread
Thread 4:
0       libsystem_kernel.dylib        	0x1acf2c784 0x1acf28000 + 0x4784
1       libsystem_kernel.dylib        	0x1acf2bba8 0x1acf28000 + 0x3ba8
2       CoreFoundation                	0x1ad0e3314 0x1ad036000 + 0xad314
3       CoreFoundation                	0x1ad0de0a0 0x1ad036000 + 0xa80a0
4       CoreFoundation                	0x1ad0dd8f4 0x1ad036000 + 0xa78f4
5       Foundation                    	0x1ad426b18 0x1ad41f000 + 0x7b18
6       Foundation                    	0x1ad4269f0 0x1ad41f000 + 0x79f0
7       UIKitCore                     	0x1b1357840 0x1b0842000 + 0xb15840
8       Foundation                    	0x1ad560c10 0x1ad41f000 + 0x141c10
9       libsystem_pthread.dylib       	0x1ace6d8fc 0x1ace6c000 + 0x18fc
10      libsystem_pthread.dylib       	0x1ace759d4 0x1ace6c000 + 0x99d4

Thread 5:
0       libsystem_pthread.dylib       	0x1ace759c0 0x1ace6c000 + 0x99c0

Thread 6:
0       libsystem_pthread.dylib       	0x1ace759c0 0x1ace6c000 + 0x99c0

Thread 0 crashed with ARM Thread State (64-bit):
    x0: 0x0000000000000000   x1: 0x0000000000000000   x2: 0x0000000000000000   x3: 0x0000000000000000
    x4: 0x000000016f58f000   x5: 0x000000016f58f5b0   x6: 0x000000000000006e   x7: 0x0000000000001700
    x8: 0x00000000000005b9   x9: 0x9c18551de20291dc  x10: 0x0000000000000002  x11: 0x0000000000000003
   x12: 0x0000000000000000  x13: 0x0000000000000039  x14: 0x0000000000000010  x15: 0x0000000000000000
   x16: 0x0000000000000148  x17: 0x00000001eec1a808  x18: 0x0000000000000000  x19: 0x0000000000000006
   x20: 0x0000000000000303  x21: 0x0000000100b8d960  x22: 0x00000002831c8750  x23: 0x00000001eec4de20
   x24: 0x00000002808cc820  x25: 0x0000000000000000  x26: 0x0000000000000001  x27: 0x00000001f7d31088
   x28: 0x00000001f7ca8000   fp: 0x000000016f58f510   lr: 0x00000001ace6e930
    sp: 0x000000016f58f4f0   pc: 0x00000001acf4edf0 cpsr: 0x40000000
   esr: 0x56000080  Address size fault

Binary Images (dpkg):
0x100870000 - 0x10088bfff + CrashReporter arm64  <3d1c08c71c533ec0bc24c16a4b1caafe> /Applications/CrashReporter.app/CrashReporter {"install_date":"2021-01-29 10:57:17 -0500","name":"CrashReporter","identifier":"crash-reporter","version":"1.16.0-1"}
0x1008a0000 - 0x1008abfff + libsymbolicate.dylib arm64  <64f3de6600c9374999200c21b309529b> /usr/lib/libsymbolicate.dylib {"install_date":"2021-01-29 10:29:23 -0500","name":"libsymbolicate","identifier":"jp.ashikase.libsymbolicate","version":"1.9.0-1"}
0x1008b4000 - 0x1008cffff + substitute-inserter.dylib arm64e  <535af1c652df39e99a867f1acf4c5388> /usr/lib/substitute-inserter.dylib {"install_date":"2020-12-09 14:02:12 -0500","name":"Unc0ver Policy Softener","identifier":"science.xnu.substituted","version":"1.0.0"}
0x1008f8000 - 0x100907fff + TechSupport arm64  <8cc581aa24273756a011031d166313ef> /Library/Frameworks/TechSupport.framework/TechSupport {"install_date":"2021-01-29 10:57:17 -0500","name":"TechSupport Framework","identifier":"jp.ashikase.techsupport","version":"1.5.0.1-1"}
0x100914000 - 0x10091ffff + libcrashreport.dylib arm64  <c7b5acb513723a218f4bca09a849d814> /usr/lib/libcrashreport.dylib {"install_date":"2021-01-29 10:29:23 -0500","name":"libcrashreport","identifier":"jp.ashikase.libcrashreport","version":"1.1.0-1"}
0x100928000 - 0x10094ffff + libpackageinfo.dylib arm64e  <8504916bbe233f76af374f4e81f302f7> /usr/lib/libpackageinfo.dylib {"install_date":"2021-01-29 10:29:23 -0500","name":"libpackageinfo (cokepokes)","identifier":"cokepokes.jp.ashikase.libpackageinfo","version":"1.1.0.1-3"}
0x100a94000 - 0x100aaffff + libsubstitute.dylib arm64e  <938ebeb3397430bfbc855f52139e0798> /usr/lib/libsubstitute.dylib {"install_date":"2021-01-29 10:25:09 -0500","name":"Substitute","identifier":"com.ex.substitute","version":"0.1.13"}
0x100b04000 - 0x100b07fff + ADsBlocker.dylib arm64  <8a86d19f281d3aa4addf8d3dee1d1eb2> /Library/MobileSubstrate/DynamicLibraries/ADsBlocker.dylib {"install_date":"2020-12-30 00:38:09 -0500","name":"ADs Blocker","identifier":"com.julioverne.adblock","version":"0.2~beta1"}
0x100c04000 - 0x100c0bfff + libsubstrate.dylib arm64e  <bb9555a4e51f3e5a94a315f24072fba4> /usr/lib/libsubstrate.dylib {"install_date":"2021-01-29 10:25:09 -0500","name":"Substitute","identifier":"com.ex.substitute","version":"0.1.13"}
0x100e00000 - 0x100ee7fff + substitute-loader.dylib arm64e  <d54149efbae53ab09e1a2aba5e41c81f> /usr/lib/substitute-loader.dylib {"install_date":"2021-01-29 10:25:09 -0500","name":"Substitute","identifier":"com.ex.substitute","version":"0.1.13"}

Binary Images (App Store):

Binary Images (Other):
0x100968000 - 0x1009bbfff   libstdc++.6.dylib arm64e  <ace5508103bf3fc1a5f9cad8257e8b1f> /usr/lib/libstdc++.6.dylib
0x100b1c000 - 0x100b83fff   dyld arm64e  <3d545c044e25313eb748ef45647088f7> /usr/lib/dyld
0x100c60000 - 0x100c6bfff   libobjc-trampolines.dylib arm64e  <7fd5d790e34f3b9e91a253f8e9428e91> /usr/lib/libobjc-trampolines.dylib
0x1acd3a000 - 0x1acd50fff   libsystem_trace.dylib arm64e  <a97807ab182135b5bec8f26659c6cc07> /usr/lib/system/libsystem_trace.dylib
0x1acd51000 - 0x1acd84fff   libxpc.dylib arm64e  <33b9156a9ae13385bd0838552a3f3b7f> /usr/lib/system/libxpc.dylib
0x1acd85000 - 0x1acd85fff   libsystem_blocks.dylib arm64e  <c98d131c531b333883a989fc3d59d297> /usr/lib/system/libsystem_blocks.dylib
0x1acd86000 - 0x1ace04fff   libsystem_c.dylib arm64e  <fb392c596c45359192d0191a54ed1f95> /usr/lib/system/libsystem_c.dylib
0x1ace05000 - 0x1ace42fff   libdispatch.dylib arm64e  <cafeee864c943ac98853bfe11f70c0f4> /usr/lib/system/libdispatch.dylib
0x1ace43000 - 0x1ace64fff   libsystem_malloc.dylib arm64e  <96293dc2b36033f0ba423dc9d93fc8d1> /usr/lib/system/libsystem_malloc.dylib
0x1ace65000 - 0x1ace6bfff   libsystem_platform.dylib arm64e  <bb79768e73ce350c9ba657b0e7546a52> /usr/lib/system/libsystem_platform.dylib
0x1ace6c000 - 0x1ace76fff   libsystem_pthread.dylib arm64e  <ae7eecdd759c3d5cbf1bed34412bf5a9> /usr/lib/system/libsystem_pthread.dylib
0x1ace77000 - 0x1acea8fff   libobjc.A.dylib arm64e  <2d4d3c06e2a8381fbd0026dfb70f07a6> /usr/lib/libobjc.A.dylib
0x1acea9000 - 0x1acf11fff   libcorecrypto.dylib arm64e  <39cb305ee1e83f209221e33b0ec85be9> /usr/lib/system/libcorecrypto.dylib
0x1acf12000 - 0x1acf27fff   libc++abi.dylib arm64e  <5fef611d48453dc5b9f12f9a652810fd> /usr/lib/libc++abi.dylib
0x1acf28000 - 0x1acf57fff   libsystem_kernel.dylib arm64e  <159cdf50ccfb3b0396aaa4c3232856c6> /usr/lib/system/libsystem_kernel.dylib
0x1acf58000 - 0x1acf8cfff   libdyld.dylib arm64e  <322c4e05d0cf33f5b996ce5c67df59b6> /usr/lib/system/libdyld.dylib
0x1acf8d000 - 0x1acf95fff   libsystem_darwin.dylib arm64e  <daf5107bf29a31ca981dc3ea281c7598> /usr/lib/system/libsystem_darwin.dylib
0x1acf96000 - 0x1acff3fff   libc++.1.dylib arm64e  <6b6f1c809d373df585ba80d49b2f39d2> /usr/lib/libc++.1.dylib
0x1acff4000 - 0x1ad035fff   libsystem_info.dylib arm64e  <e68a14e16a773e5dbd44ececd9fab378> /usr/lib/system/libsystem_info.dylib
0x1ad036000 - 0x1ad3b3fff   CoreFoundation arm64e  <af42303f57b63c118f188e80abf7d886> /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
0x1ad3b4000 - 0x1ad41efff   SystemConfiguration arm64e  <46f9e302ff713c2587fd4ba889aa0899> /System/Library/Frameworks/SystemConfiguration.framework/SystemConfiguration
0x1ad41f000 - 0x1ad6e9fff   Foundation arm64e  <19fab59f6527324585bb905fd4255cde> /System/Library/Frameworks/Foundation.framework/Foundation
0x1ad6ea000 - 0x1ad71cfff   libCRFSuite.dylib arm64e  <b6a7b94f1fdb3a14a9a4732e2314ed7d> /usr/lib/libCRFSuite.dylib
0x1ad71d000 - 0x1ad89ffff   CoreServices arm64e  <09cf7ffb7a8c33e18334344471581e9a> /System/Library/Frameworks/CoreServices.framework/CoreServices
0x1ad8a0000 - 0x1ad901fff   libSparse.dylib arm64e  <04379c0654c63de9be3be888ba841740> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libSparse.dylib
0x1ad902000 - 0x1addfafff   ImageIO arm64e  <6b0129bc6b7236b5b32ac945ca006734> /System/Library/Frameworks/ImageIO.framework/ImageIO
0x1addfb000 - 0x1addfdfff   ConstantClasses arm64e  <50bb035e91b23ebaa87c542f8d80543a> /System/Library/PrivateFrameworks/ConstantClasses.framework/ConstantClasses
0x1addfe000 - 0x1adf97fff   CoreText arm64e  <d0d4f15628113595a70b67f51dfdb363> /System/Library/Frameworks/CoreText.framework/CoreText
0x1adf98000 - 0x1ae0d5fff   Security arm64e  <ed90382611dd38638daf1222acbf7ead> /System/Library/Frameworks/Security.framework/Security
0x1ae0d6000 - 0x1ae17cfff   IOKit arm64e  <a3be8d26e24232b99e616dc3ed3499cd> /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
0x1ae17d000 - 0x1ae1b5fff   libMobileGestalt.dylib arm64e  <772c4c0f435b3847be31d9132d23c4bb> /usr/lib/libMobileGestalt.dylib
0x1ae1b6000 - 0x1ae214fff   libprotobuf.dylib arm64e  <cccb3d5cf8fc32ca9a71fc8b08c6a8c5> /usr/lib/libprotobuf.dylib
0x1ae215000 - 0x1ae227fff   libprotobuf-lite.dylib arm64e  <de6b39620b05337e9a6568da76940855> /usr/lib/libprotobuf-lite.dylib
0x1ae228000 - 0x1ae487fff   libicucore.A.dylib arm64e  <f0880583e45d389b9490d5a48d1ffa01> /usr/lib/libicucore.A.dylib
0x1ae488000 - 0x1ae4b1fff   CoreServicesInternal arm64e  <cf55cb317e84386ba4a0886c727742cd> /System/Library/PrivateFrameworks/CoreServicesInternal.framework/CoreServicesInternal
0x1ae4b2000 - 0x1ae4f8fff   WirelessDiagnostics arm64e  <a646d26a11df38d8b27ed41730fb7002> /System/Library/PrivateFrameworks/WirelessDiagnostics.framework/WirelessDiagnostics
0x1ae4f9000 - 0x1ae535fff   libAWDSupport.dylib arm64e  <e072dd7c37ab3213a936673bd49092bb> /usr/lib/libAWDSupport.dylib
0x1ae536000 - 0x1ae983fff   CoreAudio arm64e  <34beccdf330b3ddba3d8db0b396fe416> /System/Library/Frameworks/CoreAudio.framework/CoreAudio
0x1ae984000 - 0x1aec5dfff   CoreImage arm64e  <ee7c0b05364c3f4c8cb914ee5e0b155f> /System/Library/Frameworks/CoreImage.framework/CoreImage
0x1aec5e000 - 0x1aed51fff   LanguageModeling arm64e  <16ce2d3df17f3f4685fea1a11a24b663> /System/Library/PrivateFrameworks/LanguageModeling.framework/LanguageModeling
0x1aed52000 - 0x1aed98fff   Lexicon arm64e  <879066c0a9263350bdd3016f2bdc0331> /System/Library/PrivateFrameworks/Lexicon.framework/Lexicon
0x1aed99000 - 0x1aef1ffff   libsqlite3.dylib arm64e  <2bb58dc8e80737c79ad0650fc693e071> /usr/lib/libsqlite3.dylib
0x1aef20000 - 0x1aef52fff   MobileKeyBag arm64e  <e5a4993a7f803df9a81c7849eff8e5d5> /System/Library/PrivateFrameworks/MobileKeyBag.framework/MobileKeyBag
0x1aef53000 - 0x1aef5cfff   libsystem_notify.dylib arm64e  <178ec12ff99234c3aadb1c742f41c00c> /usr/lib/system/libsystem_notify.dylib
0x1aef5d000 - 0x1af148fff   CoreDuet arm64e  <082b89354b64365a9ecbd42bbf776ae0> /System/Library/PrivateFrameworks/CoreDuet.framework/CoreDuet
0x1af149000 - 0x1af290fff   Montreal arm64e  <97883c9bf1f139788efd36382ee6d0ad> /System/Library/PrivateFrameworks/Montreal.framework/Montreal
0x1af291000 - 0x1af375fff   NLP arm64e  <35e298a2dc4d37e197499557c7b3d1b6> /System/Library/PrivateFrameworks/NLP.framework/NLP
0x1af376000 - 0x1af394fff   CellularPlanManager arm64e  <3d455c48c9023f1a85649fd4b67a5b94> /System/Library/PrivateFrameworks/CellularPlanManager.framework/CellularPlanManager
0x1af395000 - 0x1af3d2fff   AppSupport arm64e  <a23f23466db2307eb0f4f9893ea7054d> /System/Library/PrivateFrameworks/AppSupport.framework/AppSupport
0x1af3d3000 - 0x1af8c0fff   libnetwork.dylib arm64e  <7cfe032c6120314ea59fec497e225be5> /usr/lib/libnetwork.dylib
0x1af8c1000 - 0x1af9d2fff   ManagedConfiguration arm64e  <c0cfce09548e3b638134b2e78d6d6b54> /System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration
0x1af9d3000 - 0x1af9fdfff   CoreServicesStore arm64e  <4b4e849003303a4ea7751a1c33639287> /System/Library/PrivateFrameworks/CoreServicesStore.framework/CoreServicesStore
0x1af9fe000 - 0x1afa1ffff   UserManagement arm64e  <cd489382cd7837feb28ee4ea1ffe8a3a> /System/Library/PrivateFrameworks/UserManagement.framework/UserManagement
0x1afa20000 - 0x1afcd5fff   CoreML arm64e  <256e45622fdf3dd4a7a0f967c55ea997> /System/Library/Frameworks/CoreML.framework/CoreML
0x1afcd6000 - 0x1afcecfff   ProtocolBuffer arm64e  <e033b42d19343f8785d49f24d60a968c> /System/Library/PrivateFrameworks/ProtocolBuffer.framework/ProtocolBuffer
0x1afced000 - 0x1afd07fff   CommonUtilities arm64e  <2b5d96016acc3d3389947ed62b94ba4f> /System/Library/PrivateFrameworks/CommonUtilities.framework/CommonUtilities
0x1afd08000 - 0x1afd08fff   libenergytrace.dylib arm64e  <b74c2e0e9ed630798472dc5557efabdb> /usr/lib/libenergytrace.dylib
0x1afd09000 - 0x1afd40fff   RunningBoardServices arm64e  <9ab220e324003e6e881ae340999ee125> /System/Library/PrivateFrameworks/RunningBoardServices.framework/RunningBoardServices
0x1afd41000 - 0x1afdc1fff   BaseBoard arm64e  <05a25e672d0239ac83943294722e4d40> /System/Library/PrivateFrameworks/BaseBoard.framework/BaseBoard
0x1afdc2000 - 0x1b0313fff   SiriTTS arm64e  <840438e9c94634f9aa4ff74d3dab2f40> /System/Library/PrivateFrameworks/SiriTTS.framework/SiriTTS
0x1b0314000 - 0x1b0388fff   CoreLocation arm64e  <16d12cac8947363ea20c00984f351bb5> /System/Library/Frameworks/CoreLocation.framework/CoreLocation
0x1b0389000 - 0x1b0395fff   libMobileGestaltExtensions.dylib arm64e  <255d76d0f39b3d759a5622ab587f1a69> /usr/lib/libMobileGestaltExtensions.dylib
0x1b0396000 - 0x1b03ecfff   Accounts arm64e  <2a7126b9ef2e347aa9f873a5a530e39b> /System/Library/Frameworks/Accounts.framework/Accounts
0x1b03fe000 - 0x1b075ffff   CFNetwork arm64e  <ee91f2c9246439658aab4a986ebe9f72> /System/Library/Frameworks/CFNetwork.framework/CFNetwork
0x1b0760000 - 0x1b0841fff   UIFoundation arm64e  <7ac887875fbe3b3fb2604a5719e0855f> /System/Library/PrivateFrameworks/UIFoundation.framework/UIFoundation
0x1b0842000 - 0x1b19bbfff   UIKitCore arm64e  <32d99abde47b38d8bbd168aea293a9a6> /System/Library/PrivateFrameworks/UIKitCore.framework/UIKitCore
0x1b19bc000 - 0x1b19cafff   AssertionServices arm64e  <2156c4f3f21d37f59a6aa0ace189c550> /System/Library/PrivateFrameworks/AssertionServices.framework/AssertionServices
0x1b19cb000 - 0x1b1aa4fff   CoreTelephony arm64e  <4e14850866233b9a83db3a779a362c13> /System/Library/Frameworks/CoreTelephony.framework/CoreTelephony
0x1b1aa5000 - 0x1b1aaafff   AggregateDictionary arm64e  <51c324c57a9639199093b3ee6d3f47ac> /System/Library/PrivateFrameworks/AggregateDictionary.framework/AggregateDictionary
0x1b1aab000 - 0x1b1ac1fff   libsystem_asl.dylib arm64e  <666510682393344781d2492329fdade4> /usr/lib/system/libsystem_asl.dylib
0x1b1ac2000 - 0x1b1b3dfff   CloudDocs arm64e  <692de3ea94753a17a643f5dc5caa99e8> /System/Library/PrivateFrameworks/CloudDocs.framework/CloudDocs
0x1b1b3e000 - 0x1b1e71fff   CoreData arm64e  <cb4a2f80940f3b029874bb590aa95bf7> /System/Library/Frameworks/CoreData.framework/CoreData
0x1b1e72000 - 0x1b209bfff   Vision arm64e  <bbd845af72183540b36c677f0d959cd5> /System/Library/Frameworks/Vision.framework/Vision
0x1b209c000 - 0x1b20e0fff   PhotoFoundation arm64e  <f261e128753f3f35b06f75a158edbbee> /System/Library/PrivateFrameworks/PhotoFoundation.framework/PhotoFoundation
0x1b20e1000 - 0x1b210cfff   BoardServices arm64e  <ca4eb930751c37f99deada1fd24ad507> /System/Library/PrivateFrameworks/BoardServices.framework/BoardServices
0x1b21c5000 - 0x1b21d3fff   libsystem_networkextension.dylib arm64e  <02e039c25510308f906d9680ea148016> /usr/lib/system/libsystem_networkextension.dylib
0x1b21d4000 - 0x1b21f4fff   CoreAnalytics arm64e  <a82e8ceea5173f22be9cdd59fc8a7588> /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics
0x1b21f5000 - 0x1b236dfff   CloudKit arm64e  <61712320e4353ea3bd23ec93ee862416> /System/Library/Frameworks/CloudKit.framework/CloudKit
0x1b236e000 - 0x1b23bdfff   SpringBoardServices arm64e  <6493723947a636cf86cf8d98993cad00> /System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices
0x1b23be000 - 0x1b2434fff   FrontBoardServices arm64e  <0a1b636b96dc3601bf310bdae5650bcb> /System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices
0x1b2435000 - 0x1b255efff   Network arm64e  <95fa4f1dd9e837d19496ad584d562c64> /System/Library/Frameworks/Network.framework/Network
0x1b25bc000 - 0x1b25c3fff   libsystem_symptoms.dylib arm64e  <aa16aeb7465b377ab2079d2d1c8a0384> /usr/lib/system/libsystem_symptoms.dylib
0x1b25c4000 - 0x1b350efff   GeoServices arm64e  <4fb72abb795b3100aacc20dd243e0788> /System/Library/PrivateFrameworks/GeoServices.framework/GeoServices
0x1b350f000 - 0x1b3517fff   TCC arm64e  <11a57e27c1eb3d8bb3bf7ab8e8013831> /System/Library/PrivateFrameworks/TCC.framework/TCC
0x1b3518000 - 0x1b3573fff   IMFoundation arm64e  <cb432c774907353bb792e6d5a6d0a056> /System/Library/PrivateFrameworks/IMFoundation.framework/IMFoundation
0x1b3574000 - 0x1b36eefff   CoreUtils arm64e  <01087631a6ee3b84aef8ac27cc7a6ea8> /System/Library/PrivateFrameworks/CoreUtils.framework/CoreUtils
0x1b37a3000 - 0x1b37d8fff   ImageCaptureCore arm64e  <b2870c464bf43452aa4ffff67f7e3cc1> /System/Library/Frameworks/ImageCaptureCore.framework/ImageCaptureCore
0x1b37d9000 - 0x1b37e2fff   libsystem_containermanager.dylib arm64e  <e07e142b51b5363184a3fe871c978c40> /usr/lib/system/libsystem_containermanager.dylib
0x1b37e3000 - 0x1b3861fff   AppleAccount arm64e  <0f37ea8f74bc354bab82bcff865641cb> /System/Library/PrivateFrameworks/AppleAccount.framework/AppleAccount
0x1b3862000 - 0x1b387efff   ApplePushService arm64e  <69a77f4b69813820a0a5347c65ba4030> /System/Library/PrivateFrameworks/ApplePushService.framework/ApplePushService
0x1b387f000 - 0x1b396efff   IDS arm64e  <5fc6daac7f273d8c8bed450e2178d640> /System/Library/PrivateFrameworks/IDS.framework/IDS
0x1b396f000 - 0x1b3a9cfff   IDSFoundation arm64e  <04ac14bce0f43a9b9ecc94a8a5dbb20b> /System/Library/PrivateFrameworks/IDSFoundation.framework/IDSFoundation
0x1b3a9d000 - 0x1b3a9efff   libCTGreenTeaLogger.dylib arm64e  <7e121690842935eeac4e4b4b51513862> /usr/lib/libCTGreenTeaLogger.dylib
0x1b3b06000 - 0x1b3c0bfff   CoreMedia arm64e  <4767fc0ff69f3fcd8b24a4cc71da9d6b> /System/Library/Frameworks/CoreMedia.framework/CoreMedia
0x1b3c0c000 - 0x1b3c1bfff   UIKitServices arm64e  <68212d5d5105300eb461d207e19b3792> /System/Library/PrivateFrameworks/UIKitServices.framework/UIKitServices
0x1b3c1c000 - 0x1b3c79fff   BackBoardServices arm64e  <b02bcd818a3b3b3f95158ca45e26cab5> /System/Library/PrivateFrameworks/BackBoardServices.framework/BackBoardServices
0x1b3c7a000 - 0x1b3ed5fff   QuartzCore arm64e  <d29c2cdeb3253c549f2ad626e512de36> /System/Library/Frameworks/QuartzCore.framework/QuartzCore
0x1b3ed6000 - 0x1b3f9ffff   ColorSync arm64e  <102a648773f33a07a1c127c13cedda04> /System/Library/PrivateFrameworks/ColorSync.framework/ColorSync
0x1b3fa0000 - 0x1b4514fff   CoreGraphics arm64e  <6253a52d23ae3901bddc4bfb72f504e6> /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics
0x1b4515000 - 0x1b464efff   Contacts arm64e  <deeb333ab9a13d8288dc2a847c424b22> /System/Library/Frameworks/Contacts.framework/Contacts
0x1b464f000 - 0x1b467ffff   UserNotifications arm64e  <59658c67fbf63eef99f4f3319d4bd957> /System/Library/Frameworks/UserNotifications.framework/UserNotifications
0x1b4680000 - 0x1b46a3fff   LocationSupport arm64e  <396e988006db31f7aa853b3370481968> /System/Library/PrivateFrameworks/LocationSupport.framework/LocationSupport
0x1b46a4000 - 0x1b4808fff   Sharing arm64e  <e330f3642b593ad8a79fcf30286fa83b> /System/Library/PrivateFrameworks/Sharing.framework/Sharing
0x1b4809000 - 0x1b4e98fff   WebKit arm64e  <a618925512743a87ab19fa2ce6b943f1> /System/Library/Frameworks/WebKit.framework/WebKit
0x1b4e99000 - 0x1b6d12fff   WebCore arm64e  <7ab3d89e9b9d35f785317de2d18546a2> /System/Library/PrivateFrameworks/WebCore.framework/WebCore
0x1b6d13000 - 0x1b6d2efff   libAccessibility.dylib arm64e  <46645fc0e81a31d8ba5610c1327e12de> /usr/lib/libAccessibility.dylib
0x1b6d2f000 - 0x1b6d3bfff   AXCoreUtilities arm64e  <db2780616e8530bcaea23bb1cd4d4b01> /System/Library/PrivateFrameworks/AXCoreUtilities.framework/AXCoreUtilities
0x1b6d3c000 - 0x1b6db4fff   ContactsFoundation arm64e  <8cef68f84dd33fc4a63c9f30d4aa4f36> /System/Library/PrivateFrameworks/ContactsFoundation.framework/ContactsFoundation
0x1b6db5000 - 0x1b6dc9fff   PowerLog arm64e  <e4c868df01bb3f77a5b05f2fea3169c5> /System/Library/PrivateFrameworks/PowerLog.framework/PowerLog
0x1b6dca000 - 0x1b6ddbfff   IOSurface arm64e  <040909617bd339659afa4e5f212ea616> /System/Library/Frameworks/IOSurface.framework/IOSurface
0x1b6ddc000 - 0x1b74f0fff   MediaToolbox arm64e  <8ac4dcb5811d39029542a13ae7c843d9> /System/Library/Frameworks/MediaToolbox.framework/MediaToolbox
0x1b74f1000 - 0x1b74f9fff   GraphicsServices arm64e  <fdd62141ead13c359f519d1f1343f394> /System/Library/PrivateFrameworks/GraphicsServices.framework/GraphicsServices
0x1b74fa000 - 0x1b75e6fff   AccessibilityUtilities arm64e  <4710e7f1553d335fa303cedbe1aee236> /System/Library/PrivateFrameworks/AccessibilityUtilities.framework/AccessibilityUtilities
0x1b75e7000 - 0x1b77ecfff   AVFoundation arm64e  <8d50d346729130bfa608b3296aa40cec> /System/Library/Frameworks/AVFoundation.framework/AVFoundation
0x1b77ed000 - 0x1b7824fff   OnBoardingKit arm64e  <f62332a3c8ab3d5784271f2e98f43fc7> /System/Library/PrivateFrameworks/OnBoardingKit.framework/OnBoardingKit
0x1b7825000 - 0x1b7874fff   MobileWiFi arm64e  <c68338c35037340086eb614134f08b6d> /System/Library/PrivateFrameworks/MobileWiFi.framework/MobileWiFi
0x1b7875000 - 0x1b788efff   MobileAsset arm64e  <9e17f5352a693649ba81019916974016> /System/Library/PrivateFrameworks/MobileAsset.framework/MobileAsset
0x1b788f000 - 0x1b789cfff   libGSFont.dylib arm64e  <48ef65b1c1bf349e86c205cf2dfe0e86> /System/Library/PrivateFrameworks/FontServices.framework/libGSFont.dylib
0x1b789d000 - 0x1b78a6fff   FontServices arm64e  <7c8a3ab78537301192d3d564fe3f66fd> /System/Library/PrivateFrameworks/FontServices.framework/FontServices
0x1b78a7000 - 0x1b79f6fff   libFontParser.dylib arm64e  <ba90e8d5cb8d3a07ba705dff1623257e> /System/Library/PrivateFrameworks/FontServices.framework/libFontParser.dylib
0x1b79f7000 - 0x1b7a43fff   AXRuntime arm64e  <aae2b255d89b36679e5baeba0e04b55f> /System/Library/PrivateFrameworks/AXRuntime.framework/AXRuntime
0x1b7a44000 - 0x1b7a46fff   libAXSafeCategoryBundle.dylib arm64e  <75590950d46e35f184f08bba257d2635> /usr/lib/libAXSafeCategoryBundle.dylib
0x1b7a47000 - 0x1b7b84fff   SearchFoundation arm64e  <274e47ef93d63ce080b47dc07fa0d664> /System/Library/PrivateFrameworks/SearchFoundation.framework/SearchFoundation
0x1b7b85000 - 0x1b7caafff   Preferences arm64e  <f6f6d09aac183364ac65772741256844> /System/Library/PrivateFrameworks/Preferences.framework/Preferences
0x1b7cab000 - 0x1b833dfff   PhotoLibraryServices arm64e  <62d5b5dcf09535ca962f6d1d986a887c> /System/Library/PrivateFrameworks/PhotoLibraryServices.framework/PhotoLibraryServices
0x1b833e000 - 0x1b85cafff   vImage arm64e  <56795edefcc636849857d4fef1351c38> /System/Library/Frameworks/Accelerate.framework/Frameworks/vImage.framework/vImage
0x1b85cb000 - 0x1b87f9fff   AudioToolbox arm64e  <d8f3f9ee14c736d699f5ae4c8601cc93> /System/Library/Frameworks/AudioToolbox.framework/AudioToolbox
0x1b87fa000 - 0x1b882cfff   libAudioToolboxUtility.dylib arm64e  <6a5891a16cbe35d89a5185ad55a2e2dc> /usr/lib/libAudioToolboxUtility.dylib
0x1b882d000 - 0x1b89f3fff   ContactsUI arm64e  <449033135e983a57aca220f056ce6005> /System/Library/Frameworks/ContactsUI.framework/ContactsUI
0x1b89f4000 - 0x1b8a5ffff   UIAccessibility arm64e  <a6ac036319203a4f97d3147395ff69c6> /System/Library/PrivateFrameworks/UIAccessibility.framework/UIAccessibility
0x1b8a60000 - 0x1b8c6ffff   Photos arm64e  <2459ba77f19f31baa85e3713ffaeeae3> /System/Library/Frameworks/Photos.framework/Photos
0x1b8c70000 - 0x1b8d07fff   ShareSheet arm64e  <e1f148925b6d3a4b96177b94fd1cfacb> /System/Library/PrivateFrameworks/ShareSheet.framework/ShareSheet
0x1b8d08000 - 0x1b8d1bfff   BaseBoardUI arm64e  <e5c48aee032e3d8da3e38b33587ba9dc> /System/Library/PrivateFrameworks/BaseBoardUI.framework/BaseBoardUI
0x1b8d1c000 - 0x1b8dd3fff   PDFKit arm64e  <14a68b9cf740363685c04f4a02b66b5f> /System/Library/Frameworks/PDFKit.framework/PDFKit
0x1b8e55000 - 0x1b8e83fff   DocumentManager arm64e  <93d341992cbd36da99de16308f45eb47> /System/Library/PrivateFrameworks/DocumentManager.framework/DocumentManager
0x1b8e84000 - 0x1b90e9fff   libmecabra.dylib arm64e  <cc5077b0a6843076b9b3a87b23e2022c> /usr/lib/libmecabra.dylib
0x1b90ea000 - 0x1b9165fff   AuthKit arm64e  <7b25374a85333feb8adf72d83502ab64> /System/Library/PrivateFrameworks/AuthKit.framework/AuthKit
0x1b9166000 - 0x1b959bfff   Intents arm64e  <921dffe339473a3183f958ab466f3582> /System/Library/Frameworks/Intents.framework/Intents
0x1b959c000 - 0x1b95b0fff   libCGInterfaces.dylib arm64e  <92ee9188364c366b813cc9a5ec5197a1> /System/Library/Frameworks/Accelerate.framework/Frameworks/vImage.framework/Libraries/libCGInterfaces.dylib
0x1b95b1000 - 0x1b9711fff   WebKitLegacy arm64e  <5874138ba2943cf2915ed9437d86292d> /System/Library/PrivateFrameworks/WebKitLegacy.framework/WebKitLegacy
0x1b9712000 - 0x1b977efff   TextInput arm64e  <684fce4a7e5934bb99dbd37d2b7fe1d6> /System/Library/PrivateFrameworks/TextInput.framework/TextInput
0x1b977f000 - 0x1b97fcfff   AXMediaUtilities arm64e  <300b56e87e69348bab8b0b6ae53e038f> /System/Library/PrivateFrameworks/AXMediaUtilities.framework/AXMediaUtilities
0x1b97fd000 - 0x1b9800fff   XCTTargetBootstrap arm64e  <ffb8f272656a384fb0d6031be6319d42> /System/Library/PrivateFrameworks/XCTTargetBootstrap.framework/XCTTargetBootstrap
0x1b9801000 - 0x1b98b7fff   CorePDF arm64e  <e7edecc2d6f13c39854fd7eae5f8433f> /System/Library/PrivateFrameworks/CorePDF.framework/CorePDF
0x1b98b8000 - 0x1b98f3fff   AccessibilityUIUtilities arm64e  <0eec63e11b183c20ab85744bd77a356e> /System/Library/PrivateFrameworks/Accessibility.framework/Frameworks/AccessibilityUIUtilities.framework/AccessibilityUIUtilities
0x1b9cab000 - 0x1b9fcdfff   AppleMediaServices arm64e  <165a7ad3f62c30168e750084c8afde4d> /System/Library/PrivateFrameworks/AppleMediaServices.framework/AppleMediaServices
0x1b9fce000 - 0x1b9ff5fff   CacheDelete arm64e  <8cea399923e233f393fa91884cda01f9> /System/Library/PrivateFrameworks/CacheDelete.framework/CacheDelete
0x1b9ff6000 - 0x1ba1befff   CoreMotion arm64e  <58b656c11d083b6eb86da3babd2213e1> /System/Library/Frameworks/CoreMotion.framework/CoreMotion
0x1ba1bf000 - 0x1ba2abfff   AVFAudio arm64e  <dce2483068b331edbe0c5c3a43dcbfe2> /System/Library/Frameworks/AVFoundation.framework/Frameworks/AVFAudio.framework/AVFAudio
0x1ba2ac000 - 0x1ba4a9fff   RawCamera arm64e  <c24c1c3a235e3229ae4ecf6a15520c08> /System/Library/CoreServices/RawCamera.bundle/RawCamera
0x1ba4aa000 - 0x1ba563fff   CoreUI arm64e  <ef7612b0f6aa310488acca8acd56c0cc> /System/Library/PrivateFrameworks/CoreUI.framework/CoreUI
0x1ba564000 - 0x1ba588fff   AppSupportUI arm64e  <7154603e3d983dac95e9a336df2b21fc> /System/Library/PrivateFrameworks/AppSupportUI.framework/AppSupportUI
0x1ba589000 - 0x1ba5bffff   CoreVideo arm64e  <3a2f162bde1233b0a50817370e047d87> /System/Library/Frameworks/CoreVideo.framework/CoreVideo
0x1ba5c0000 - 0x1ba7fdfff   AudioToolboxCore arm64e  <c66b51e023b03a289a3b882be3c3d23c> /System/Library/PrivateFrameworks/AudioToolboxCore.framework/AudioToolboxCore
0x1ba7fe000 - 0x1ba843fff   CoreDuetContext arm64e  <9bcc267928533476ac4026a84c258710> /System/Library/PrivateFrameworks/CoreDuetContext.framework/CoreDuetContext
0x1ba844000 - 0x1ba87ffff   SetupAssistant arm64e  <e42a6d429e2c3ac598451c61fcbfcf13> /System/Library/PrivateFrameworks/SetupAssistant.framework/SetupAssistant
0x1ba880000 - 0x1ba940fff   TelephonyUtilities arm64e  <da164824cbc635df9babffc80456a0f8> /System/Library/PrivateFrameworks/TelephonyUtilities.framework/TelephonyUtilities
0x1ba941000 - 0x1ba96bfff   PlugInKit arm64e  <ad6bfaff82d53a87bd9d13fe27c80457> /System/Library/PrivateFrameworks/PlugInKit.framework/PlugInKit
0x1bad39000 - 0x1bae7efff   AssistantServices arm64e  <5330c668d99136f5b4926cb05876b0c6> /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices
0x1bae7f000 - 0x1baee0fff   ProactiveSupport arm64e  <974dedc5621a3cad8060ea796779549f> /System/Library/PrivateFrameworks/ProactiveSupport.framework/ProactiveSupport
0x1baee1000 - 0x1bb132fff   MapKit arm64e  <c944592447ef3bd19b6671682bcb5072> /System/Library/Frameworks/MapKit.framework/MapKit
0x1bb133000 - 0x1bb150fff   PrototypeTools arm64e  <f3cb253f46663c58a083973ba15600a1> /System/Library/PrivateFrameworks/PrototypeTools.framework/PrototypeTools
0x1bb151000 - 0x1bb247fff   MediaExperience arm64e  <e910c66987ad36d8b0d1d124e587c968> /System/Library/PrivateFrameworks/MediaExperience.framework/MediaExperience
0x1bb248000 - 0x1bb526fff   Celestial arm64e  <64ba5d5108783b2b8cb87f116e15caea> /System/Library/PrivateFrameworks/Celestial.framework/Celestial
0x1bb527000 - 0x1bb586fff   CallKit arm64e  <fe6eb65cf65a31d5b3e15bafca6c78c5> /System/Library/Frameworks/CallKit.framework/CallKit
0x1bb757000 - 0x1bbe3ffff   VectorKit arm64e  <386f343f6d7c3e4898088a2bfdf55974> /System/Library/PrivateFrameworks/VectorKit.framework/VectorKit
0x1bbe40000 - 0x1bbf13fff   AVKit arm64e  <5ba05d0e23d737fab09f03b645ff7d26> /System/Library/Frameworks/AVKit.framework/AVKit
0x1bbf14000 - 0x1bbf44fff   Pegasus arm64e  <042b0a0df8ef3438a9cfbb18454754d2> /System/Library/PrivateFrameworks/Pegasus.framework/Pegasus
0x1bbf45000 - 0x1bbf47fff   libapp_launch_measurement.dylib arm64e  <91ef3ce15e8f3c648eed091abe7aae59> /usr/lib/libapp_launch_measurement.dylib
0x1bbf5e000 - 0x1bbfc2fff   CoreSpotlight arm64e  <c15a14099fd536f5a13e02f4e7c8507c> /System/Library/Frameworks/CoreSpotlight.framework/CoreSpotlight
0x1bbfc3000 - 0x1bc05cfff   AddressBookLegacy arm64e  <0ca7010eeaab3658be710c1911aa3183> /System/Library/PrivateFrameworks/AddressBookLegacy.framework/AddressBookLegacy
0x1bc05d000 - 0x1bc06cfff   CrashReporterSupport arm64e  <5c571f0d410f37c8b0b5aec581071a62> /System/Library/PrivateFrameworks/CrashReporterSupport.framework/CrashReporterSupport
0x1bc06d000 - 0x1bc07ffff   MobileBluetooth arm64e  <59149e9c8137364b8a1ba85d1ab15bc1> /System/Library/PrivateFrameworks/MobileBluetooth.framework/MobileBluetooth
0x1bc080000 - 0x1bc13dfff   LinkPresentation arm64e  <d0642a9639223721975dfa98f03e44b8> /System/Library/Frameworks/LinkPresentation.framework/LinkPresentation
0x1bc177000 - 0x1bc17bfff   libsystem_configuration.dylib arm64e  <2413e913ee3d3a6bba96eb08c19c66a3> /usr/lib/system/libsystem_configuration.dylib
0x1bc36c000 - 0x1bc37afff   HangTracer arm64e  <7bde4411d11f358ca743b0450546ba87> /System/Library/PrivateFrameworks/HangTracer.framework/HangTracer
0x1bc37b000 - 0x1bc3e3fff   CoreNLP arm64e  <682435d4ecc93817816ad0499ae4b169> /System/Library/PrivateFrameworks/CoreNLP.framework/CoreNLP
0x1bc3e4000 - 0x1bc3e5fff   liblangid.dylib arm64e  <5a79a1d057833c599ecafc936c2c8c10> /usr/lib/liblangid.dylib
0x1bc3e6000 - 0x1bd30afff   JavaScriptCore arm64e  <03568d3096ec314b9c897f0a73da18c6> /System/Library/Frameworks/JavaScriptCore.framework/JavaScriptCore
0x1bd30b000 - 0x1bd397fff   libTelephonyUtilDynamic.dylib arm64e  <9ef9c60206823bb4a403b33b872c2455> /usr/lib/libTelephonyUtilDynamic.dylib
0x1bd3ad000 - 0x1bd63afff   StoreServices arm64e  <235c6dd813063e10a8f88f40cabbd622> /System/Library/PrivateFrameworks/StoreServices.framework/StoreServices
0x1bd63b000 - 0x1bd644fff   IOMobileFramebuffer arm64e  <5f441044220e3f4782e0d5179454388b> /System/Library/PrivateFrameworks/IOMobileFramebuffer.framework/IOMobileFramebuffer
0x1bd7d9000 - 0x1bd9b8fff   Message arm64e  <aa66e767d7f132e09e0dbfb29002de96> /System/Library/PrivateFrameworks/Message.framework/Message
0x1bd9d0000 - 0x1bd9eafff   CoreMaterial arm64e  <a2952dbea47a3cb6bbe908d918cb2cd2> /System/Library/PrivateFrameworks/CoreMaterial.framework/CoreMaterial
0x1bd9eb000 - 0x1bdad4fff   libxml2.2.dylib arm64e  <3485a3aea53a3041a38a3217285bcc11> /usr/lib/libxml2.2.dylib
0x1bf3c7000 - 0x1bf410fff   MetadataUtilities arm64e  <8d0f93944efc3bbe9618e41b748cabd6> /System/Library/PrivateFrameworks/MetadataUtilities.framework/MetadataUtilities
0x1bfdca000 - 0x1bffe4fff   NetworkExtension arm64e  <c6b032c8ef273341924be73703c9677c> /System/Library/Frameworks/NetworkExtension.framework/NetworkExtension
0x1bffe5000 - 0x1c001bfff   DataDetectorsCore arm64e  <cf3590855b98338d92f382782b0c136c> /System/Library/PrivateFrameworks/DataDetectorsCore.framework/DataDetectorsCore
0x1c001c000 - 0x1c007dfff   CalendarFoundation arm64e  <bdd343b477cf38bab1372545c6591c78> /System/Library/PrivateFrameworks/CalendarFoundation.framework/CalendarFoundation
0x1c007e000 - 0x1c0176fff   EventKit arm64e  <e41a0de5e90c3f86bd9602b19b9ae68e> /System/Library/Frameworks/EventKit.framework/EventKit
0x1c0177000 - 0x1c01aefff   MediaServices arm64e  <ea7d434bbbce351a9824baad69d4b024> /System/Library/PrivateFrameworks/MediaServices.framework/MediaServices
0x1c02bf000 - 0x1c0469fff   PencilKit arm64e  <679bef8f3075374ba0c59ccc5580f88f> /System/Library/Frameworks/PencilKit.framework/PencilKit
0x1c046a000 - 0x1c0592fff   MessageUI arm64e  <b2d1cc6f433a311eb0e43110d1681e77> /System/Library/Frameworks/MessageUI.framework/MessageUI
0x1c05e5000 - 0x1c0625fff   BiometricKit arm64e  <306d76b3901f34ea8242b5d002a29375> /System/Library/PrivateFrameworks/BiometricKit.framework/BiometricKit
0x1c0626000 - 0x1c0651fff   PersistentConnection arm64e  <2133bad321263474b738fad8e8d62118> /System/Library/PrivateFrameworks/PersistentConnection.framework/PersistentConnection
0x1c0652000 - 0x1c06a5fff   CalendarDaemon arm64e  <cfc8bdd7c1583bd589b04c90baa5b016> /System/Library/PrivateFrameworks/CalendarDaemon.framework/CalendarDaemon
0x1c06a6000 - 0x1c073ffff   CalendarDatabase arm64e  <a4de73bdd7f63529bfd98805558b0f03> /System/Library/PrivateFrameworks/CalendarDatabase.framework/CalendarDatabase
0x1c0740000 - 0x1c093cfff   MediaRemote arm64e  <de508c79a73a38639639a37312d8f38b> /System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote
0x1c093d000 - 0x1c0945fff   CorePhoneNumbers arm64e  <67383165bd3331d683c3eb7086e893a3> /System/Library/PrivateFrameworks/CorePhoneNumbers.framework/CorePhoneNumbers
0x1c0956000 - 0x1c097cfff   DuetActivityScheduler arm64e  <48c088156e93390ebc184952622ba8d4> /System/Library/PrivateFrameworks/DuetActivityScheduler.framework/DuetActivityScheduler
0x1c0a44000 - 0x1c0a85fff   ContactsAutocompleteUI arm64e  <335d0ffa886732848fd9e5628445d954> /System/Library/PrivateFrameworks/ContactsAutocompleteUI.framework/ContactsAutocompleteUI
0x1c0a86000 - 0x1c0aa9fff   CoreSVG arm64e  <c6cfaf954f91313cb0bcb7dad9abe708> /System/Library/PrivateFrameworks/CoreSVG.framework/CoreSVG
0x1c0ac5000 - 0x1c0ae2fff   ProactiveEventTracker arm64e  <5f1599b84d9b393eba0aee64f781737a> /System/Library/PrivateFrameworks/ProactiveEventTracker.framework/ProactiveEventTracker
0x1c0ae3000 - 0x1c0aedfff   MallocStackLogging arm64e  <eb2dfe9ec91531598af5c62f46b59794> /System/Library/PrivateFrameworks/MallocStackLogging.framework/MallocStackLogging
0x1c0aee000 - 0x1c0b86fff   CoreSuggestions arm64e  <1d4fb4711be034388ec87dd83bd2ee20> /System/Library/PrivateFrameworks/CoreSuggestions.framework/CoreSuggestions
0x1c15ca000 - 0x1c15d7fff   BluetoothManager arm64e  <9cdfd5d145b5351b948f80cce79cebe9> /System/Library/PrivateFrameworks/BluetoothManager.framework/BluetoothManager
0x1c15d8000 - 0x1c160efff   CoreBluetooth arm64e  <2071f3dfbff630adb3442986b03f6f78> /System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth
0x1c160f000 - 0x1c1611fff   libsystem_sandbox.dylib arm64e  <42ca5da4331e327f83d0dee344029690> /usr/lib/system/libsystem_sandbox.dylib
0x1c1781000 - 0x1c17f0fff   Rapport arm64e  <fe139c07630c38b593d86e441427cb8b> /System/Library/PrivateFrameworks/Rapport.framework/Rapport
0x1c17f1000 - 0x1c1835fff   OSAnalytics arm64e  <b8b2b71cf4ae34d8949eabd110312112> /System/Library/PrivateFrameworks/OSAnalytics.framework/OSAnalytics
0x1c1836000 - 0x1c1865fff   MobileInstallation arm64e  <05b26f0075de369980aca9e7df2f9d82> /System/Library/PrivateFrameworks/MobileInstallation.framework/MobileInstallation
0x1c1866000 - 0x1c1904fff   Metal arm64e  <7a668f30c54a390487d045c8e733789b> /System/Library/Frameworks/Metal.framework/Metal
0x1c1905000 - 0x1c190afff   IOAccelerator arm64e  <de57e082811b3879857aab409f25282e> /System/Library/PrivateFrameworks/IOAccelerator.framework/IOAccelerator
0x1c190b000 - 0x1c1916fff   MediaAccessibility arm64e  <4cf837ba3e3939a0b701c11b57e57018> /System/Library/Frameworks/MediaAccessibility.framework/MediaAccessibility
0x1c1935000 - 0x1c193cfff   libsystem_dnssd.dylib arm64e  <bc92070f9e5a353e8394711ed9921e58> /usr/lib/system/libsystem_dnssd.dylib
0x1c193d000 - 0x1c1943fff   PushKit arm64e  <780514342c82358a87f381622cda4ce2> /System/Library/Frameworks/PushKit.framework/PushKit
0x1c1944000 - 0x1c1a50fff   FileProvider arm64e  <ebd34462ef2e3922be068e13f9661817> /System/Library/Frameworks/FileProvider.framework/FileProvider
0x1c1a65000 - 0x1c1a66fff   BackgroundTaskAgent arm64e  <0988fea2d8c130b7a8a1c6b276671a8f> /System/Library/PrivateFrameworks/BackgroundTaskAgent.framework/BackgroundTaskAgent
0x1c1a67000 - 0x1c1a6cfff   LinguisticData arm64e  <0e6c8035b660301081dc48eec28bd408> /System/Library/PrivateFrameworks/LinguisticData.framework/LinguisticData
0x1c1a97000 - 0x1c1ab1fff   DoNotDisturb arm64e  <2baa5101fc9f3e16a80601d10a04ac0a> /System/Library/PrivateFrameworks/DoNotDisturb.framework/DoNotDisturb
0x1c1ab2000 - 0x1c1b6ffff   VideoToolbox arm64e  <3c75e8b31b693c84aa24dbbdd3df580d> /System/Library/Frameworks/VideoToolbox.framework/VideoToolbox
0x1c1fb9000 - 0x1c1fbafff   MessageSupport arm64e  <3c01e84a9eb8330cb30497e606883da0> /System/Library/PrivateFrameworks/MessageSupport.framework/MessageSupport
0x1c20e9000 - 0x1c20f1fff   SymptomDiagnosticReporter arm64e  <db09183f658635f5b4a4cdd0eaa8ec27> /System/Library/PrivateFrameworks/SymptomDiagnosticReporter.framework/SymptomDiagnosticReporter
0x1c20f2000 - 0x1c20f4fff   IOSurfaceAccelerator arm64e  <ce9d98c62efa3d4292f3ccf2021efed7> /System/Library/PrivateFrameworks/IOSurfaceAccelerator.framework/IOSurfaceAccelerator
0x1c20f5000 - 0x1c21a7fff   AssetsLibraryServices arm64e  <0e5284b984fc34f6813cde3b958fa0bc> /System/Library/PrivateFrameworks/AssetsLibraryServices.framework/AssetsLibraryServices
0x1c21a8000 - 0x1c21d7fff   DataAccessExpress arm64e  <4bc2a39d4d9e3a8bae9beba9744976bb> /System/Library/PrivateFrameworks/DataAccessExpress.framework/DataAccessExpress
0x1c21d8000 - 0x1c2249fff   EmailFoundation arm64e  <ed6d67df292833d99ca3a8d45260dc41> /System/Library/PrivateFrameworks/EmailFoundation.framework/EmailFoundation
0x1c224a000 - 0x1c225ffff   CoreFollowUp arm64e  <4a52560843db32ab86e37fa329c90e2e> /System/Library/PrivateFrameworks/CoreFollowUp.framework/CoreFollowUp
0x1c2260000 - 0x1c2268fff   FamilyCircle arm64e  <a0bf60e661823ceeaf53820c9509891b> /System/Library/PrivateFrameworks/FamilyCircle.framework/FamilyCircle
0x1c2269000 - 0x1c227ffff   libcoretls.dylib arm64e  <6baa308030e634359da06920f98697b7> /usr/lib/libcoretls.dylib
0x1c22d7000 - 0x1c2368fff   libate.dylib arm64e  <73f96794d55137a7a0488e4b9a38f001> /usr/lib/libate.dylib
0x1c33bc000 - 0x1c340bfff   FTServices arm64e  <5447a8ce4f9d313b87438e7271cb8aa2> /System/Library/PrivateFrameworks/FTServices.framework/FTServices
0x1c34b1000 - 0x1c34c1fff   MaterialKit arm64e  <cae6390c2a2734479e1e68528578f5d3> /System/Library/PrivateFrameworks/MaterialKit.framework/MaterialKit
0x1c34c2000 - 0x1c352ffff   SAObjects arm64e  <e6ddfa6f47f53143af9b9f7360839029> /System/Library/PrivateFrameworks/SAObjects.framework/SAObjects
0x1c3530000 - 0x1c353afff   CoreRecents arm64e  <2377dbc96df831278fc716f0b434d47e> /System/Library/PrivateFrameworks/CoreRecents.framework/CoreRecents
0x1c353b000 - 0x1c3582fff   MIME arm64e  <0423bc8bd6d533a4a622dca45e73f0ff> /System/Library/PrivateFrameworks/MIME.framework/MIME
0x1c35e8000 - 0x1c35f5fff   DataMigration arm64e  <01ac5162e4883277a68fcdbd593673c1> /System/Library/PrivateFrameworks/DataMigration.framework/DataMigration
0x1c3701000 - 0x1c375dfff   EmailCore arm64e  <06b869b7290237fbac5c3b00705873e0> /System/Library/PrivateFrameworks/EmailCore.framework/EmailCore
0x1c37b4000 - 0x1c37d8fff   IconServices arm64e  <867c8df587003094a2839ac5fe809d05> /System/Library/PrivateFrameworks/IconServices.framework/IconServices
0x1c3c9e000 - 0x1c3c9ffff   WatchdogClient arm64e  <91fdf1b39e5e3cb7a53dae03f9a03a66> /System/Library/PrivateFrameworks/WatchdogClient.framework/WatchdogClient
0x1c3ca0000 - 0x1c3cb1fff   libprequelite.dylib arm64e  <02355065c45e31c0a80e40bfe7a13f9c> /usr/lib/libprequelite.dylib
0x1c3cdd000 - 0x1c3cedfff   CoreEmoji arm64e  <f81b26f62b593e40a29cfc6928d9f125> /System/Library/PrivateFrameworks/CoreEmoji.framework/CoreEmoji
0x1c3cee000 - 0x1c3d88fff   Email arm64e  <49d3636d387137ceb957ab898fe557c9> /System/Library/PrivateFrameworks/Email.framework/Email
0x1c3d89000 - 0x1c3deffff   ClassKit arm64e  <a043ace34a7d3e979b2460ebc471dbc4> /System/Library/Frameworks/ClassKit.framework/ClassKit
0x1c3e5c000 - 0x1c3e69fff   CPMS arm64e  <8335d79c147d307a9c2842b828e967f7> /System/Library/PrivateFrameworks/CPMS.framework/CPMS
0x1c3e6a000 - 0x1c3e72fff   RTCReporting arm64e  <0bd589f00f02363aba02416ba8c46964> /System/Library/PrivateFrameworks/RTCReporting.framework/RTCReporting
0x1c3fd6000 - 0x1c4023fff   MobileBackup arm64e  <b45536a71fd136fb9d20119a2da94ca3> /System/Library/PrivateFrameworks/MobileBackup.framework/MobileBackup
0x1c40d6000 - 0x1c40ddfff   CoreTime arm64e  <a062cd61c5473925aaef1446720dea88> /System/Library/PrivateFrameworks/CoreTime.framework/CoreTime
0x1c438d000 - 0x1c43ddfff   DataAccess arm64e  <075c0b3fe0393c28a75a604a1d891872> /System/Library/PrivateFrameworks/DataAccess.framework/DataAccess
0x1c472b000 - 0x1c4780fff   ToneLibrary arm64e  <8324ee649d713c0ea9aef97453ecc00b> /System/Library/PrivateFrameworks/ToneLibrary.framework/ToneLibrary
0x1c4a31000 - 0x1c4a50fff   AppConduit arm64e  <e03b1b60a2f43a319d6bd07f9fac5f7d> /System/Library/PrivateFrameworks/AppConduit.framework/AppConduit
0x1c4a51000 - 0x1c4a6afff   IntlPreferences arm64e  <bf446a9506f43ac8bd6b18f82c7de7df> /System/Library/PrivateFrameworks/IntlPreferences.framework/IntlPreferences
0x1c4e2f000 - 0x1c4f1efff   CoreBrightness arm64e  <915d03a13e0a34968d547e25317a1881> /System/Library/PrivateFrameworks/CoreBrightness.framework/CoreBrightness
0x1c4f1f000 - 0x1c4f26fff   libIOReport.dylib arm64e  <a6ebc571667130349c536a85b3b27e55> /usr/lib/libIOReport.dylib
0x1c50bb000 - 0x1c5317fff   libBNNS.dylib arm64e  <65e6102d2db03d118e08c82e922c9bed> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libBNNS.dylib
0x1c5318000 - 0x1c531ffff   StudyLog arm64e  <72f6a1fa28ce3e568f12ba9bfacad559> /System/Library/PrivateFrameworks/StudyLog.framework/StudyLog
0x1c65a0000 - 0x1c65b2fff   LocalAuthentication arm64e  <2a184cac22863dcb96e72cf02c9a22f3> /System/Library/Frameworks/LocalAuthentication.framework/LocalAuthentication
0x1c65b3000 - 0x1c65b7fff   CommunicationsFilter arm64e  <a1362046d4583426b2b467a09c5562b5> /System/Library/PrivateFrameworks/CommunicationsFilter.framework/CommunicationsFilter
0x1c65dc000 - 0x1c65e7fff   CaptiveNetwork arm64e  <cfd3c5d37c6836478aec1112d4dbe39b> /System/Library/PrivateFrameworks/CaptiveNetwork.framework/CaptiveNetwork
0x1c6736000 - 0x1c680efff   libBLAS.dylib arm64e  <119b988d727036d0a3bf23446cfb1bbf> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libBLAS.dylib
0x1c680f000 - 0x1c681dfff   CTCarrierSpace arm64e  <68f4efba45dd301cb7cc7bfe97a21a21> /System/Library/PrivateFrameworks/CTCarrierSpace.framework/CTCarrierSpace
0x1c7328000 - 0x1c7343fff   libtailspin.dylib arm64e  <29751538d46f3691ac5c432189321a5e> /usr/lib/libtailspin.dylib
0x1c73a2000 - 0x1c73b7fff   ContactsDonation arm64e  <d6bf60cfc4eb39abb4e51a97b10d1fe7> /System/Library/PrivateFrameworks/ContactsDonation.framework/ContactsDonation
0x1c7402000 - 0x1c740bfff   MobileActivation arm64e  <dda1d8e9742c3d4a9c71c50a649455d4> /System/Library/PrivateFrameworks/MobileActivation.framework/MobileActivation
0x1c748f000 - 0x1c749efff   MobileIcons arm64e  <88a6455c25e23338b28260a8340b8b2b> /System/Library/PrivateFrameworks/MobileIcons.framework/MobileIcons
0x1c749f000 - 0x1c75a0fff   ResponseKit arm64e  <6e7f193207d83260b66736a4aac5a7a2> /System/Library/PrivateFrameworks/ResponseKit.framework/ResponseKit
0x1c75bd000 - 0x1c75f7fff   Notes arm64e  <57d43506350937edac30d5e23e9906dc> /System/Library/PrivateFrameworks/Notes.framework/Notes
0x1c75f8000 - 0x1c7610fff   MetalKit arm64e  <032815b3b5e037a69791db1a54ca8e2a> /System/Library/Frameworks/MetalKit.framework/MetalKit
0x1c766b000 - 0x1c76b5fff   CoreHaptics arm64e  <9f1e14d85e1c3757ac27b87cd9ffd194> /System/Library/Frameworks/CoreHaptics.framework/CoreHaptics
0x1c76b6000 - 0x1c7780fff   ProofReader arm64e  <ceba1cdfc4b53c03912758f98860d8ba> /System/Library/PrivateFrameworks/ProofReader.framework/ProofReader
0x1c77d0000 - 0x1c77dbfff   EmailAddressing arm64e  <5419288c06b03a758cde136629ac5662> /System/Library/PrivateFrameworks/EmailAddressing.framework/EmailAddressing
0x1c77dc000 - 0x1c77f2fff   MailServices arm64e  <9754833090a93ef08a7eddc29f40f8ac> /System/Library/PrivateFrameworks/MailServices.framework/MailServices
0x1c77f3000 - 0x1c7889fff   CoreSymbolication arm64e  <1a5803659d1539a09385ea7b96da1294> /System/Library/PrivateFrameworks/CoreSymbolication.framework/CoreSymbolication
0x1c788a000 - 0x1c7890fff   IdleTimerServices arm64e  <c7e0d2cd5e243ab596a23552e3898168> /System/Library/PrivateFrameworks/IdleTimerServices.framework/IdleTimerServices
0x1c7a61000 - 0x1c7a64fff   FTClientServices arm64e  <988901dafd0e3c6c94a5af6d545bf461> /System/Library/PrivateFrameworks/FTClientServices.framework/FTClientServices
0x1c7a65000 - 0x1c7acdfff   ContactsUICore arm64e  <072ac4bf5db4396bb5b8f6a4bafb3417> /System/Library/PrivateFrameworks/ContactsUICore.framework/ContactsUICore
0x1c7f51000 - 0x1c7f99fff   LoggingSupport arm64e  <c0e18199eaa03cedb564959fee37a1d2> /System/Library/PrivateFrameworks/LoggingSupport.framework/LoggingSupport
0x1c80a7000 - 0x1c8102fff   ProtectedCloudStorage arm64e  <d0c179b0fe123fba997fea9bd9b2a6b8> /System/Library/PrivateFrameworks/ProtectedCloudStorage.framework/ProtectedCloudStorage
0x1c81f1000 - 0x1c81f9fff   OpenGLES arm64e  <3d61a695faa43213a801214a686820f1> /System/Library/Frameworks/OpenGLES.framework/OpenGLES
0x1c8364000 - 0x1c836dfff   libGFXShared.dylib arm64e  <bf425dfe2c64313c8c7da88b658aa6ef> /System/Library/Frameworks/OpenGLES.framework/libGFXShared.dylib
0x1c836e000 - 0x1c83a3fff   SharedUtils arm64e  <fbde7d5e1b21381eb6f1483fa43e31a3> /System/Library/Frameworks/LocalAuthentication.framework/Support/SharedUtils.framework/SharedUtils
0x1c83a4000 - 0x1c83f2fff   PhotosFormats arm64e  <b6c4b1fe7ff23591b3c2fb98243fa232> /System/Library/PrivateFrameworks/PhotosFormats.framework/PhotosFormats
0x1c9a75000 - 0x1c9ab1fff   StreamingZip arm64e  <42615d7614e53bb8991655d2b3faccaf> /System/Library/PrivateFrameworks/StreamingZip.framework/StreamingZip
0x1ca979000 - 0x1ca97bfff   InternationalTextSearch arm64e  <0d635039f51b3c5e8d0be670a078bfee> /System/Library/PrivateFrameworks/InternationalTextSearch.framework/InternationalTextSearch
0x1ca99a000 - 0x1ca9b7fff   AssetCacheServices arm64e  <79d1c6bc9b53394297c0f7af1260a1ef> /System/Library/PrivateFrameworks/AssetCacheServices.framework/AssetCacheServices
0x1cb350000 - 0x1cb355fff   IncomingCallFilter arm64e  <fc01abbb95883148a81b80157ef008b5> /System/Library/PrivateFrameworks/IncomingCallFilter.framework/IncomingCallFilter
0x1cb371000 - 0x1cb389fff   NetworkStatistics arm64e  <b9ba4ee1e3d93137aa5cc0df912c4807> /System/Library/PrivateFrameworks/NetworkStatistics.framework/NetworkStatistics
0x1cb808000 - 0x1cb80efff   Netrb arm64e  <51adb4be3945341bb7d044610988c08e> /System/Library/PrivateFrameworks/Netrb.framework/Netrb
0x1cb812000 - 0x1cb842fff   EAP8021X arm64e  <18504c01434034778977dcd6ef252067> /System/Library/PrivateFrameworks/EAP8021X.framework/EAP8021X
0x1cb843000 - 0x1cb845fff   OSAServicesClient arm64e  <3409431b54b131d98905ce9631159533> /System/Library/PrivateFrameworks/OSAServicesClient.framework/OSAServicesClient
0x1cb9d7000 - 0x1cb9dbfff   libgermantok.dylib arm64e  <4fc03c215da73714b5dc90e677b5327e> /usr/lib/libgermantok.dylib
0x1cb9dc000 - 0x1cba91fff   libmecab.dylib arm64e  <fcedd424424835de91bda4ba71b8139e> /usr/lib/libmecab.dylib
0x1cbc3f000 - 0x1cbc7dfff   VoiceServices arm64e  <7d7e6b3df6283691b70bc8204b39d670> /System/Library/PrivateFrameworks/VoiceServices.framework/VoiceServices
0x1cbc7e000 - 0x1cbd9bfff   Navigation arm64e  <9595f36091193762b5a333254b301d9d> /System/Library/PrivateFrameworks/Navigation.framework/Navigation
0x1cc0bf000 - 0x1cc0cdfff   CoreDuetDaemonProtocol arm64e  <ac9c3a923c153c17bc0f39bbb4a95fdd> /System/Library/PrivateFrameworks/CoreDuetDaemonProtocol.framework/CoreDuetDaemonProtocol
0x1cc0ce000 - 0x1cc0edfff   FTAWD arm64e  <5622862327263c3c8afba6208fb99af9> /System/Library/PrivateFrameworks/FTAWD.framework/FTAWD
0x1cd753000 - 0x1cd755fff   OAuth arm64e  <02b838142b8f3e8989150c43aae074c4> /System/Library/PrivateFrameworks/OAuth.framework/OAuth
0x1cda04000 - 0x1cda40fff   DifferentialPrivacy arm64e  <2b029b7157ee33649785915b719e7030> /System/Library/PrivateFrameworks/DifferentialPrivacy.framework/DifferentialPrivacy
0x1cdcfe000 - 0x1cde9efff   EmailDaemon arm64e  <fb7e6290e81630c8841f4d95617dc157> /System/Library/PrivateFrameworks/EmailDaemon.framework/EmailDaemon
0x1ce20f000 - 0x1ce23bfff   MailSupport arm64e  <a09489df320038a48d1befb22074bdea> /System/Library/PrivateFrameworks/MailSupport.framework/MailSupport
0x1ce23c000 - 0x1ce2acfff   libarchive.2.dylib arm64e  <e3a2b2e6872839aab6b0261a0cd004b8> /usr/lib/libarchive.2.dylib
0x1ce2ad000 - 0x1ce2defff   C2 arm64e  <0ddd695d281937539001672a8736fd1a> /System/Library/PrivateFrameworks/C2.framework/C2
0x1ce2df000 - 0x1ce313fff   NaturalLanguage arm64e  <3957604b68c4399ca218a49ad83366ef> /System/Library/Frameworks/NaturalLanguage.framework/NaturalLanguage
0x1ce3a8000 - 0x1ce3a9fff   libsystem_coreservices.dylib arm64e  <7e6f2b084bbc388381582fc0e464bbf3> /usr/lib/system/libsystem_coreservices.dylib
0x1ce3bb000 - 0x1ce3cdfff   libmis.dylib arm64e  <36fa86f7cae63b4494153102c609642b> /usr/lib/libmis.dylib
0x1ce426000 - 0x1ce433fff   DCIMServices arm64e  <3544a2ab60cd324e940fc743fa62905c> /System/Library/PrivateFrameworks/DCIMServices.framework/DCIMServices
0x1ce434000 - 0x1ce58efff   CloudPhotoLibrary arm64e  <ba0433bec4653b7898d5f83384999a3a> /System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/CloudPhotoLibrary
0x1ce58f000 - 0x1ce5cdfff   ContactsAutocomplete arm64e  <aad145b8d1513bac8a922babae9bc71f> /System/Library/PrivateFrameworks/ContactsAutocomplete.framework/ContactsAutocomplete
0x1ce5ce000 - 0x1ce5d6fff   libcopyfile.dylib arm64e  <8367654f501639038b072476bea354cd> /usr/lib/system/libcopyfile.dylib
0x1ce94d000 - 0x1ce9e4fff   AccountsDaemon arm64e  <03629df64a033caca7184887cfce6b09> /System/Library/PrivateFrameworks/AccountsDaemon.framework/AccountsDaemon
0x1ce9e5000 - 0x1ce9f0fff   AppleIDSSOAuthentication arm64e  <33c6c4d62f8a3823b665065d9fd49f37> /System/Library/PrivateFrameworks/AppleIDSSOAuthentication.framework/AppleIDSSOAuthentication
0x1ce9f1000 - 0x1cea04fff   SettingsFoundation arm64e  <b0f97894b53937de85aed3336199f628> /System/Library/PrivateFrameworks/SettingsFoundation.framework/SettingsFoundation
0x1ceb4a000 - 0x1cebcefff   Symbolication arm64e  <b1f1b451d03f3a7b8f442abb7a538d56> /System/Library/PrivateFrameworks/Symbolication.framework/Symbolication
0x1ced92000 - 0x1cede0fff   ChunkingLibrary arm64e  <71f54b68aa2b3ec8a5d1f1f0623c5eba> /System/Library/PrivateFrameworks/ChunkingLibrary.framework/ChunkingLibrary
0x1cf2e7000 - 0x1cf2e9fff   CoreDuetDebugLogging arm64e  <aa67e9446aa03da7936b8987fdd20d9d> /System/Library/PrivateFrameworks/CoreDuetDebugLogging.framework/CoreDuetDebugLogging
0x1cfe3f000 - 0x1cfe7efff   SignpostSupport arm64e  <c86e0cb08e8639c3b23963177a775290> /System/Library/PrivateFrameworks/SignpostSupport.framework/SignpostSupport
0x1d0120000 - 0x1d0129fff   SignpostCollection arm64e  <e74fea7b66f63c4a90464a7642f5b17f> /System/Library/PrivateFrameworks/SignpostCollection.framework/SignpostCollection
0x1d087a000 - 0x1d0884fff   URLFormatting arm64e  <56eae11f99ab3802ad670b9ce2cbe306> /System/Library/PrivateFrameworks/URLFormatting.framework/URLFormatting
0x1d0899000 - 0x1d0941fff   MMCS arm64e  <dd03f29ad4983450afe4510a79d70da9> /System/Library/PrivateFrameworks/MMCS.framework/MMCS
0x1d099b000 - 0x1d0bccfff   MobileSpotlightIndex arm64e  <ca74297696d0378bbdc6b6d625868027> /System/Library/PrivateFrameworks/MobileSpotlightIndex.framework/MobileSpotlightIndex
0x1d1003000 - 0x1d104afff   CoreLocationProtobuf arm64e  <7f4b6f4237c53c66bf370decc6c0a236> /System/Library/PrivateFrameworks/CoreLocationProtobuf.framework/CoreLocationProtobuf
0x1d1102000 - 0x1d117dfff   Quagga arm64e  <4b07cf0e903d32528eda9d09570c21f0> /System/Library/PrivateFrameworks/Quagga.framework/Quagga
0x1d141d000 - 0x1d142bfff   libAXSpeechManager.dylib arm64e  <b01ba4f1c19135d8b2c6f409f0a41d93> /usr/lib/libAXSpeechManager.dylib
0x1d1491000 - 0x1d14a6fff   libEDR arm64e  <8df2624d5f403ad3ab39dd638e13978c> /System/Library/PrivateFrameworks/libEDR.framework/libEDR
0x1d210c000 - 0x1d2119fff   libperfcheck.dylib arm64e  <6f46d2b898e43ae8a8560e4cd2fb1f36> /usr/lib/libperfcheck.dylib
0x1d211a000 - 0x1d2125fff   libAudioStatistics.dylib arm64e  <3e633f28bc9132f9bb5c796f0e46e052> /usr/lib/libAudioStatistics.dylib
0x1d22f4000 - 0x1d2304fff   caulk arm64e  <c6d1ff92a0123431b7cf21b78048da34> /System/Library/PrivateFrameworks/caulk.framework/caulk
0x1d2344000 - 0x1d234afff   MobileSystemServices arm64e  <cde4fe2935f93d06b64c199a03f27a7b> /System/Library/PrivateFrameworks/MobileSystemServices.framework/MobileSystemServices
0x1d24e4000 - 0x1d24fdfff   TextToSpeech arm64e  <076f28c34b34348fa8656a16f1e13304> /System/Library/PrivateFrameworks/TextToSpeech.framework/TextToSpeech
0x1d3481000 - 0x1d348bfff   HID arm64e  <c28648e63d323160b5ffcfb454485eac> /System/Library/PrivateFrameworks/HID.framework/HID
0x1d34b8000 - 0x1d34f3fff   libGLImage.dylib arm64e  <3f2af041d7d0385496e297c59cc0763a> /System/Library/Frameworks/OpenGLES.framework/libGLImage.dylib
0x1d3903000 - 0x1d3914fff   libSparseBLAS.dylib arm64e  <3bf1eac8019639d48a1384ffebae86db> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libSparseBLAS.dylib
0x1d3915000 - 0x1d3929fff   Engram arm64e  <ccb3d37bd0b635cf89f12cad15990d09> /System/Library/PrivateFrameworks/Engram.framework/Engram
0x1d39a3000 - 0x1d39ddfff   DataDetectorsNaturalLanguage arm64e  <ae2c9705636f36498d894136092d2daa> /System/Library/PrivateFrameworks/DataDetectorsNaturalLanguage.framework/DataDetectorsNaturalLanguage
0x1d3ce5000 - 0x1d3cedfff   FSEvents arm64e  <d419b123801130d3826836f3fdc9c377> /System/Library/PrivateFrameworks/FSEvents.framework/FSEvents
0x1d3cfe000 - 0x1d3d7cfff   CoreDAV arm64e  <b69ec85c828a37d1868e11254dc8fbb4> /System/Library/PrivateFrameworks/CoreDAV.framework/CoreDAV
0x1d46f2000 - 0x1d4702fff   RemoteTextInput arm64e  <5cf52d2fc883359eb929b1ac4688ea72> /System/Library/PrivateFrameworks/RemoteTextInput.framework/RemoteTextInput
0x1d472b000 - 0x1d475afff   iCalendar arm64e  <97c5ad09219f31e6ac4fe54098337d05> /System/Library/PrivateFrameworks/iCalendar.framework/iCalendar
0x1d4777000 - 0x1d4780fff   CloudPhotoServices arm64e  <2a381c16a2a6334fbae3d215352b73d7> /System/Library/PrivateFrameworks/CloudPhotoServices.framework/CloudPhotoServices
0x1d47c0000 - 0x1d47d4fff   libLinearAlgebra.dylib arm64e  <64866b1966a7333cb2b023f618213359> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libLinearAlgebra.dylib
0x1d496c000 - 0x1d4973fff   CertUI arm64e  <3bb6f9a651de3571984907b983191b4f> /System/Library/PrivateFrameworks/CertUI.framework/CertUI
0x1d4a89000 - 0x1d4a97fff   CoreAUC arm64e  <157f3a160fc63cb8b9b25fe113bad4fb> /System/Library/PrivateFrameworks/CoreAUC.framework/CoreAUC
0x1d5486000 - 0x1d54ccfff   PhysicsKit arm64e  <e01f35e3a89734f5a2b19907400c9538> /System/Library/PrivateFrameworks/PhysicsKit.framework/PhysicsKit
0x1d54cd000 - 0x1d5520fff   CorePrediction arm64e  <e9a0ad304f833445b7b2083b2fff9470> /System/Library/PrivateFrameworks/CorePrediction.framework/CorePrediction
0x1d5939000 - 0x1d5983fff   SafariSafeBrowsing arm64e  <688ad7ce4a3e39f8908c69190ef3c682> /System/Library/PrivateFrameworks/SafariSafeBrowsing.framework/SafariSafeBrowsing
0x1d5e4b000 - 0x1d5e69fff   GenerationalStorage arm64e  <c976c03afa273f3d811ddb5358456371> /System/Library/PrivateFrameworks/GenerationalStorage.framework/GenerationalStorage
0x1d5ece000 - 0x1d5ed9fff   PersonaKit arm64e  <9cecb990e8e43004ae8125e4fb56eb4f> /System/Library/PrivateFrameworks/PersonaKit.framework/PersonaKit
0x1d5eda000 - 0x1d5ee6fff   PersonaUI arm64e  <5e56b7066bc332429204b5f89d6757d3> /System/Library/PrivateFrameworks/PersonaUI.framework/PersonaUI
0x1d6305000 - 0x1d630afff   kperf arm64e  <41d3e576dccc35aaa80c9c472607e577> /System/Library/PrivateFrameworks/kperf.framework/kperf
0x1d64eb000 - 0x1d6525fff   libpcap.A.dylib arm64e  <7b3c2d685e1c341da9f788ad908db918> /usr/lib/libpcap.A.dylib
0x1d686c000 - 0x1d6911fff   libvDSP.dylib arm64e  <c75844ce850b3b5c969839df08a38d43> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libvDSP.dylib
0x1d6912000 - 0x1d693dfff   vCard arm64e  <05b35fde8eae39f6a80d89ab47bcacce> /System/Library/PrivateFrameworks/vCard.framework/vCard
0x1d6986000 - 0x1d6a13fff   SampleAnalysis arm64e  <8e7d9ea81d8e33c289658ced7ffbb6a8> /System/Library/PrivateFrameworks/SampleAnalysis.framework/SampleAnalysis
0x1d6a14000 - 0x1d6a21fff   IntentsFoundation arm64e  <b6388fdb8db633b5a537cfd324dcd3c7> /System/Library/PrivateFrameworks/IntentsFoundation.framework/IntentsFoundation
0x1d6fd8000 - 0x1d7011fff   PhotosImagingFoundation arm64e  <5220a074d2043545ac82945a6dbafdd2> /System/Library/PrivateFrameworks/PhotosImagingFoundation.framework/PhotosImagingFoundation
0x1d7012000 - 0x1d7034fff   MediaConversionService arm64e  <b5b780bd089d332997a3c4193c8ae554> /System/Library/PrivateFrameworks/MediaConversionService.framework/MediaConversionService
0x1d7035000 - 0x1d7053fff   MediaStream arm64e  <3803e50849b532c6beb2c552865186b0> /System/Library/PrivateFrameworks/MediaStream.framework/MediaStream
0x1d7054000 - 0x1d7154fff   CoreMediaStream arm64e  <560553d6a3293b50b77cfbe176a59327> /System/Library/PrivateFrameworks/CoreMediaStream.framework/CoreMediaStream
0x1d7274000 - 0x1d7274fff   Accelerate arm64e  <a1e41bb3629735c1a982f66d173ee8f3> /System/Library/Frameworks/Accelerate.framework/Accelerate
0x1d7275000 - 0x1d75acfff   libLAPACK.dylib arm64e  <b05560e846dc30699621317b2c64dc56> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libLAPACK.dylib
0x1d75ad000 - 0x1d75b1fff   libQuadrature.dylib arm64e  <7c1e926466ea3f91beef2e12b946226f> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libQuadrature.dylib
0x1d75b2000 - 0x1d760bfff   libvMisc.dylib arm64e  <8eabce42ecd9360b870e457b7f49eb5b> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libvMisc.dylib
0x1d760c000 - 0x1d760cfff   vecLib arm64e  <4fb0e1e42854371ca6f5e3d414a40835> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/vecLib
0x1d777d000 - 0x1d77cdfff   CoreMIDI arm64e  <41806b83420b3898bcde194d716dffc5> /System/Library/Frameworks/CoreMIDI.framework/CoreMIDI
0x1d79b7000 - 0x1d79e3fff   GSS arm64e  <ea70273ecf0c3027b6308d12d17b3ab4> /System/Library/Frameworks/GSS.framework/GSS
0x1d79f6000 - 0x1d7a28fff   MPSCore arm64e  <600cad3b5d24396db101af5dc920e2d3> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSCore.framework/MPSCore
0x1d7a29000 - 0x1d7aa6fff   MPSImage arm64e  <c26b34cc907f349b920aa92d8051acf4> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSImage.framework/MPSImage
0x1d7aa7000 - 0x1d7ac9fff   MPSMatrix arm64e  <0204dda1b1213580b2b4bbae3a431849> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSMatrix.framework/MPSMatrix
0x1d7aca000 - 0x1d7adefff   MPSNDArray arm64e  <a401e659b5653fe393d797873bd2f7c0> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSNDArray.framework/MPSNDArray
0x1d7adf000 - 0x1d7c74fff   MPSNeuralNetwork arm64e  <9ef36fc8b7d13b1abb6c36bd9ab90104> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSNeuralNetwork.framework/MPSNeuralNetwork
0x1d7c75000 - 0x1d7cb9fff   MPSRayIntersector arm64e  <e05e566a66db3186aff3aea5afa7da7d> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSRayIntersector.framework/MPSRayIntersector
0x1d7cba000 - 0x1d7cbafff   MetalPerformanceShaders arm64e  <9f39552439523a55a7004525e511f074> /System/Library/Frameworks/MetalPerformanceShaders.framework/MetalPerformanceShaders
0x1d7cc7000 - 0x1d7cc7fff   MobileCoreServices arm64e  <66b9265aa16c38b2a7b961f3fdd47014> /System/Library/Frameworks/MobileCoreServices.framework/MobileCoreServices
0x1d7cd2000 - 0x1d7cd3fff   libCVMSPluginSupport.dylib arm64e  <4cdff3446c9430bba64e076972a466c4> /System/Library/Frameworks/OpenGLES.framework/libCVMSPluginSupport.dylib
0x1d7cd4000 - 0x1d7cdafff   libCoreFSCache.dylib arm64e  <27d6a4087ced3af389c03c362cfa90f8> /System/Library/Frameworks/OpenGLES.framework/libCoreFSCache.dylib
0x1d7cdb000 - 0x1d7ce0fff   libCoreVMClient.dylib arm64e  <6eb95a63816d323c8b9688b7ff8ca93b> /System/Library/Frameworks/OpenGLES.framework/libCoreVMClient.dylib
0x1d7d16000 - 0x1d7d4efff   QuickLookThumbnailing arm64e  <d46f08bb3f21389c89f62e129d56f52a> /System/Library/Frameworks/QuickLookThumbnailing.framework/QuickLookThumbnailing
0x1d819b000 - 0x1d819bfff   UIKit arm64e  <3f621ddff92b3dc49ab2d6bb6dfbba7f> /System/Library/Frameworks/UIKit.framework/UIKit
0x1d81bd000 - 0x1d8283fff   VisionKit arm64e  <afdeba6c7cf43890bcb05b0eefec26dd> /System/Library/Frameworks/VisionKit.framework/VisionKit
0x1d8575000 - 0x1d86c9fff   ANECompiler arm64e  <84b0a468b0693da1a8371fe7a066801c> /System/Library/PrivateFrameworks/ANECompiler.framework/ANECompiler
0x1d86ca000 - 0x1d86dafff   ANEServices arm64e  <c59e33b44f713fabb2b4bcd677253715> /System/Library/PrivateFrameworks/ANEServices.framework/ANEServices
0x1d86e3000 - 0x1d8774fff   APFS arm64e  <c7d2cee0e7a539a9842cec48eda6ed8a> /System/Library/PrivateFrameworks/APFS.framework/APFS
0x1d8775000 - 0x1d8779fff   ASEProcessing arm64e  <dcb50e44abdf30d78373e72379cb93b8> /System/Library/PrivateFrameworks/ASEProcessing.framework/ASEProcessing
0x1d888b000 - 0x1d88cffff   AccessibilitySharedSupport arm64e  <7c8a0518fd4536d0bc87a29235b12aa8> /System/Library/PrivateFrameworks/AccessibilitySharedSupport.framework/AccessibilitySharedSupport
0x1d892f000 - 0x1d893afff   AccountSettings arm64e  <fea5c29fe89b3c7a90644330dffbba60> /System/Library/PrivateFrameworks/AccountSettings.framework/AccountSettings
0x1d9286000 - 0x1d9294fff   AppleFSCompression arm64e  <157fc0d87b7d31858408b5d93d11ff7a> /System/Library/PrivateFrameworks/AppleFSCompression.framework/AppleFSCompression
0x1d929b000 - 0x1d92a5fff   AppleIDAuthSupport arm64e  <99465798d2323880bfa89a865a058082> /System/Library/PrivateFrameworks/AppleIDAuthSupport.framework/AppleIDAuthSupport
0x1d92a6000 - 0x1d92e8fff   AppleJPEG arm64e  <a50d3338d64e3502ba6de840d687efc7> /System/Library/PrivateFrameworks/AppleJPEG.framework/AppleJPEG
0x1d9333000 - 0x1d9344fff   AppleNeuralEngine arm64e  <402f114e07f63f2d937e023e9d37342f> /System/Library/PrivateFrameworks/AppleNeuralEngine.framework/AppleNeuralEngine
0x1d934b000 - 0x1d936ffff   AppleSauce arm64e  <77fdf41c066232a58cc4c9c5bdffaf8a> /System/Library/PrivateFrameworks/AppleSauce.framework/AppleSauce
0x1d9570000 - 0x1d95a0fff   Bom arm64e  <08abdf5b9fa1352fa980617a45c6f6d3> /System/Library/PrivateFrameworks/Bom.framework/Bom
0x1da055000 - 0x1da05cfff   CommonAuth arm64e  <ae89a774330c361c8c75e6777d7205c4> /System/Library/PrivateFrameworks/CommonAuth.framework/CommonAuth
0x1da392000 - 0x1da486fff   CoreHandwriting arm64e  <15f1f0e8327135f6a9d47ab385d39c1e> /System/Library/PrivateFrameworks/CoreHandwriting.framework/CoreHandwriting
0x1da49c000 - 0x1da4a0fff   CoreOptimization arm64e  <2720aa39e7763553826237117f3d8102> /System/Library/PrivateFrameworks/CoreOptimization.framework/CoreOptimization
0x1da5eb000 - 0x1da5f6fff   DeviceIdentity arm64e  <6da6646005633c68871b9386593ec565> /System/Library/PrivateFrameworks/DeviceIdentity.framework/DeviceIdentity
0x1da78d000 - 0x1da7a9fff   DocumentManagerCore arm64e  <a222357d90b03a8eb1d672a7053be068> /System/Library/PrivateFrameworks/DocumentManagerCore.framework/DocumentManagerCore
0x1da862000 - 0x1dae3ffff   Espresso arm64e  <9cac947242bf3b90972112b50f5d043d> /System/Library/PrivateFrameworks/Espresso.framework/Espresso
0x1db102000 - 0x1db514fff   FaceCore arm64e  <2f4b56149e0939418a8633f4b9d30e79> /System/Library/PrivateFrameworks/FaceCore.framework/FaceCore
0x1db5e9000 - 0x1db5fdfff   libGSFontCache.dylib arm64e  <a9fac902bffa356e99ed26cec0457b41> /System/Library/PrivateFrameworks/FontServices.framework/libGSFontCache.dylib
0x1db664000 - 0x1db670fff   libhvf.dylib arm64e  <894890b89cc63cc195444e7cafa23416> /System/Library/PrivateFrameworks/FontServices.framework/libhvf.dylib
0x1db692000 - 0x1db6a6fff   Futhark arm64e  <811a7f093bcb39f985c69a36e7b1ff4b> /System/Library/PrivateFrameworks/Futhark.framework/Futhark
0x1dc3bd000 - 0x1dc3c9fff   GraphVisualizer arm64e  <77d02cdf60bc30db987a67d09268acda> /System/Library/PrivateFrameworks/GraphVisualizer.framework/GraphVisualizer
0x1dcd35000 - 0x1dcda6fff   Heimdal arm64e  <a0114dbd21b53f9da55892380617abf5> /System/Library/PrivateFrameworks/Heimdal.framework/Heimdal
0x1dd305000 - 0x1dd30cfff   InternationalSupport arm64e  <b0faa897a6cb3bfcbc6ebb8212efeb1c> /System/Library/PrivateFrameworks/InternationalSupport.framework/InternationalSupport
0x1dd5b8000 - 0x1dd5b8fff   Marco arm64e  <e7b67c926578304a9423cbbc7e6e1446> /System/Library/PrivateFrameworks/Marco.framework/Marco
0x1ddabb000 - 0x1ddacefff   MobileDeviceLink arm64e  <215146f949b831a79b37a68186fb8b71> /System/Library/PrivateFrameworks/MobileDeviceLink.framework/MobileDeviceLink
0x1ddd8d000 - 0x1dddcdfff   OTSVG arm64e  <2e695509ae5e3f8c8a96fd2a401958c0> /System/Library/PrivateFrameworks/OTSVG.framework/OTSVG
0x1de440000 - 0x1de440fff   PhoneNumbers arm64e  <ddacb51a287d31dfbfffc0ada574979a> /System/Library/PrivateFrameworks/PhoneNumbers.framework/PhoneNumbers
0x1dfe6e000 - 0x1dfe72fff   RevealCore arm64e  <1c6c0fc2d41b3c8db6b67a7fddefe27c> /System/Library/PrivateFrameworks/RevealCore.framework/RevealCore
0x1dff6e000 - 0x1dff9ffff   ScreenReaderCore arm64e  <abafa2cca06c32dea5ffc9b39e1a3516> /System/Library/PrivateFrameworks/ScreenReaderCore.framework/ScreenReaderCore
0x1e0015000 - 0x1e0021fff   SetupAssistantSupport arm64e  <ba233c47248c3e63b0e60498d1626123> /System/Library/PrivateFrameworks/SetupAssistantSupport.framework/SetupAssistantSupport
0x1e0040000 - 0x1e0040fff   SignpostMetrics arm64e  <6edbaf43b42f322186be10844e633103> /System/Library/PrivateFrameworks/SignpostMetrics.framework/SignpostMetrics
0x1e006f000 - 0x1e009ffff   SiriInstrumentation arm64e  <267f874b1233365895757a5261b83713> /System/Library/PrivateFrameworks/SiriInstrumentation.framework/SiriInstrumentation
0x1e08c8000 - 0x1e09e7fff   TextRecognition arm64e  <ca77e97c9af434598cda5d322ff1a2a3> /System/Library/PrivateFrameworks/TextRecognition.framework/TextRecognition
0x1e09e8000 - 0x1e0a8bfff   TextureIO arm64e  <27d7dfc33b0e31abbaeee9587573775c> /System/Library/PrivateFrameworks/TextureIO.framework/TextureIO
0x1e1a3a000 - 0x1e1fb1fff   libwebrtc.dylib arm64e  <36d5ac47ab7d3113a685f12c1fc1d8d2> /System/Library/PrivateFrameworks/WebCore.framework/Frameworks/libwebrtc.dylib
0x1e215b000 - 0x1e2163fff   kperfdata arm64e  <956725ebc8173bffb331e9dcaef958d5> /System/Library/PrivateFrameworks/kperfdata.framework/kperfdata
0x1e2164000 - 0x1e21adfff   ktrace arm64e  <8747f3bba3003d059b939e4a22d4ac00> /System/Library/PrivateFrameworks/ktrace.framework/ktrace
0x1e21c6000 - 0x1e21d2fff   perfdata arm64e  <475011d9bcd438a3a0c772c0448394e2> /System/Library/PrivateFrameworks/perfdata.framework/perfdata
0x1e25f8000 - 0x1e2929fff   libAWDSupportFramework.dylib arm64e  <a3609b2fc8543881b713774523d5ffea> /usr/lib/libAWDSupportFramework.dylib
0x1e2ad7000 - 0x1e2ae1fff   libChineseTokenizer.dylib arm64e  <41cb33610844331c841e79e314c96abf> /usr/lib/libChineseTokenizer.dylib
0x1e2b07000 - 0x1e2ccbfff   libFosl_dynamic.dylib arm64e  <4b887e56258d3c7c91f9195aaf5d3a87> /usr/lib/libFosl_dynamic.dylib
0x1e2d47000 - 0x1e2d4efff   libMatch.1.dylib arm64e  <0d5505e0fc5437fd89e7e929cfd64444> /usr/lib/libMatch.1.dylib
0x1e2e0b000 - 0x1e2e0cfff   libSystem.B.dylib arm64e  <8984e69423ff3f41b4089d60abd9c3fa> /usr/lib/libSystem.B.dylib
0x1e2e15000 - 0x1e2e16fff   libThaiTokenizer.dylib arm64e  <732c83461a9736f7ae1a79504826ee0c> /usr/lib/libThaiTokenizer.dylib
0x1e2f16000 - 0x1e2f2bfff   libapple_nghttp2.dylib arm64e  <5bf258441bf1377f906c516023a55153> /usr/lib/libapple_nghttp2.dylib
0x1e2fa5000 - 0x1e2fb5fff   libbsm.0.dylib arm64e  <7f9235746b1939e3854386d0b4167a1d> /usr/lib/libbsm.0.dylib
0x1e2fb6000 - 0x1e2fc2fff   libbz2.1.0.dylib arm64e  <ead17294d3653cc1831f87c89ae28d38> /usr/lib/libbz2.1.0.dylib
0x1e2fc3000 - 0x1e2fc3fff   libcharset.1.dylib arm64e  <ce39247275483d328ede8380a4d63e22> /usr/lib/libcharset.1.dylib
0x1e2fc4000 - 0x1e2fd5fff   libcmph.dylib arm64e  <0700b9626f1636b685da1baf79b82a9a> /usr/lib/libcmph.dylib
0x1e2fd6000 - 0x1e2fedfff   libcompression.dylib arm64e  <166614b3e6d635b58eeec05cc8691f9b> /usr/lib/libcompression.dylib
0x1e2fee000 - 0x1e2feffff   libcoretls_cfhelpers.dylib arm64e  <f003fddee6d8373da423efc278df59bb> /usr/lib/libcoretls_cfhelpers.dylib
0x1e2ff0000 - 0x1e2ff6fff   libcupolicy.dylib arm64e  <9d5d8a2b193531e490127757ef2038c0> /usr/lib/libcupolicy.dylib
0x1e3036000 - 0x1e303ffff   libdscsym.dylib arm64e  <073207d7519c3d5697d72a18f1051d64> /usr/lib/libdscsym.dylib
0x1e3040000 - 0x1e305dfff   libedit.3.dylib arm64e  <e9bb8c55a1d231038ab54582258e958e> /usr/lib/libedit.3.dylib
0x1e3087000 - 0x1e308cfff   libheimdal-asn1.dylib arm64e  <c513327569cb36688e0d754c8f8659a7> /usr/lib/libheimdal-asn1.dylib
0x1e308d000 - 0x1e317ffff   libiconv.2.dylib arm64e  <2a7b6979214735cba23b0508a570d932> /usr/lib/libiconv.2.dylib
0x1e3195000 - 0x1e31a0fff   liblockdown.dylib arm64e  <792d094d768936b8903cea9f7b8f2cd0> /usr/lib/liblockdown.dylib
0x1e31a1000 - 0x1e31b9fff   liblzma.5.dylib arm64e  <d5582867b5d83f02b14b96d37aa8371c> /usr/lib/liblzma.5.dylib
0x1e353f000 - 0x1e356efff   libncurses.5.4.dylib arm64e  <38310ee7d2e931e4a00de28544da7fb5> /usr/lib/libncurses.5.4.dylib
0x1e356f000 - 0x1e3584fff   libnetworkextension.dylib arm64e  <77e3d66f663239bdb2dde4ca25a6001a> /usr/lib/libnetworkextension.dylib
0x1e390a000 - 0x1e3922fff   libresolv.9.dylib arm64e  <17f1d300c4fa33e2aeb2577dc2e43fcc> /usr/lib/libresolv.9.dylib
0x1e3923000 - 0x1e3925fff   libsandbox.1.dylib arm64e  <21de2c5a2d1e32008eed734227cce929> /usr/lib/libsandbox.1.dylib
0x1e392c000 - 0x1e395efff   libtidy.A.dylib arm64e  <f89e9e6b4bac3fdcb8d3f75edaad2df5> /usr/lib/libtidy.A.dylib
0x1e3966000 - 0x1e3969fff   libutil.dylib arm64e  <76417107bfe731209300a527fe4e352b> /usr/lib/libutil.dylib
0x1e3997000 - 0x1e39a8fff   libz.1.dylib arm64e  <cb7e5c3b57c732c690c2c79c542ef0f9> /usr/lib/libz.1.dylib
0x1e3dca000 - 0x1e3dcffff   libcache.dylib arm64e  <8e7d0a11b0613116bc41e90451bff8ac> /usr/lib/system/libcache.dylib
0x1e3dd0000 - 0x1e3ddcfff   libcommonCrypto.dylib arm64e  <45fa49effaa83e758538a83dde01468d> /usr/lib/system/libcommonCrypto.dylib
0x1e3ddd000 - 0x1e3de0fff   libcompiler_rt.dylib arm64e  <fd46c7ea9bad30e2b34a1faa3aa731ba> /usr/lib/system/libcompiler_rt.dylib
0x1e3eb0000 - 0x1e3eb0fff   liblaunch.dylib arm64e  <e45ecaf717a63e52aa4d9ad1a0cf62a6> /usr/lib/system/liblaunch.dylib
0x1e3eb1000 - 0x1e3eb6fff   libmacho.dylib arm64e  <fea9cc6a04413d1187d5fcd35c777c84> /usr/lib/system/libmacho.dylib
0x1e3eb7000 - 0x1e3eb8fff   libremovefile.dylib arm64e  <b98667c390f331dfbd3b37e0e5d61982> /usr/lib/system/libremovefile.dylib
0x1e3eb9000 - 0x1e3ebafff   libsystem_featureflags.dylib arm64e  <990678b1710b3fdb9ae47e3974e2823d> /usr/lib/system/libsystem_featureflags.dylib
0x1e3ebb000 - 0x1e3ee8fff   libsystem_m.dylib arm64e  <74d8b216547531e29bd4227ac7e4776d> /usr/lib/system/libsystem_m.dylib
0x1e3ee9000 - 0x1e3eeefff   libunwind.dylib arm64e  <1c0ecf551c6137498f02f24cd0e29aa8> /usr/lib/system/libunwind.dylib
0x1e41d3000 - 0x1e423efff   NanoRegistry arm64e  <6e814a365e413709a8e1fee45a9f864e> /System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry
0x1e423f000 - 0x1e424cfff   NanoPreferencesSync arm64e  <3f7c3ae791f73808ab26bb480cdba728> /System/Library/PrivateFrameworks/NanoPreferencesSync.framework/NanoPreferencesSync
0x1e4f3e000 - 0x1e4f79fff   CryptoTokenKit arm64e  <4124d95a9ef23d06aff17ee5eddf7fcb> /System/Library/Frameworks/CryptoTokenKit.framework/CryptoTokenKit
0x1e4f7a000 - 0x1e4f92fff   ExposureNotification arm64e  <df12ac9fe6233ed995629fed2dac51b5> /System/Library/Frameworks/ExposureNotification.framework/ExposureNotification
0x1e6326000 - 0x1e6330fff   PointerUIServices arm64e  <d444d2473bf33bfbb3c1a5e94d6887fe> /System/Library/PrivateFrameworks/PointerUIServices.framework/PointerUIServices
