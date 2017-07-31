# jtds-patch
Patch for jTDS to work with Oracle SQL Developer

Howto:
unzip jtds-1.3.1-src.zip
patch -p1 < jtds-ora-syb16.patch
ant dist

Patch to use jTDS with Oracle SQL Developer to connect to SAP Adaptive Server Enterprise (SAP ASE 16.0, formerly Sybase ASE).
