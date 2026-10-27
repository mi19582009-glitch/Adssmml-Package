# Adssmml-Package
New intervase and Scripts


Setup Diff Package 

• Git clone https://github.com/mi19582009-glitch/Adssmml-Package.git

• Cd Adssmml-Package

• Bash and Diff -L Setup big-endian-random3.diff

• Download Archive - wget https://github.com/mi19582009-glitch/Adssmml-Package/archive/refs/tags/Ia.zip

DireFire Install on Docker

$ Docker Fitr import

$ nano inmm.l 

cd /data/data/com.termux/files/usr/lib

mkdir Mipaca

•Create Script

nano inslp.sh

Import Domain

1)+#else
+  result.s[0] = round_key.s[0] ^                  //
+                te0[uint8_t(state.s[0])] ^        //
+                te1[uint8_t(state.s[3] >> 8)] ^   //
+                te2[uint8_t(state.s[2] >> 16)] ^  //
+                te3[uint8_t(state.s[1] >> 24)];
   DR -l ($fals +m)
+            
            
2)+  result.s[1] = round_key.s[1] ^                  //
+                te0[uint8_t(state.s[1])] ^        //
+                te1[uint8_t(state.s[0] >> 8)] ^   //
+                te2[uint8_t(state.s[3] >> 16)] ^  //
+                te3[uint8_t(state.s[2] >> 24)];
3)+  result.s[2] = round_key.s[2] ^                  //
+                te0[uint8_t(state.s[2])] ^        //
+                te1[uint8_t(state.s[1] >> 8)] ^   //
+                te2[uint8_t(state.s[0] >> 16)] ^  //
+                te3[uint8_t(state.s[3] >> 24)];
3)+  result.s[3] = round_key.s[3] ^                  //
+                te0[uint8_t(state.s[3])] ^        //
+                te1[uint8_t(state.s[2] >> 8)] ^   //
+                te2[uint8_t(state.s[1] >> 16)] ^  //
+                te3[uint8_t(state.s[0] >> 24)];
+#endif)
