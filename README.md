## CSipSimple
CSipSimple is an open-source native SIP client for Android

See http://www.csipsimple.com for more info

Copyright (C) 2009-2010 Regis Montoya (http://www.r3gis.fr)
Copyright (C) 2010 Robert B. Denny, Mesa, AZ, USA (rdenny@dc3.com)

This file is part of CSipSimple


CSipSimple is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

CSipSimple is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.
If you own a pjsip commercial license you can also redistribute it
and/or modify it under the terms of the GNU Lesser General Public License
as an android library.

You should have received a copy of the GNU General Public License
along with CSipSimple.  If not, see <http://www.gnu.org/licenses/>.


Keep in mind that the entiere application rely on a library 
released under GPL license terms. Please contact them
if you want to use the LGPL dual license of csipsimple.
Copyright (C) 2003-2008 Benny Prijono <benny@prijono.org>
Copyright (C) 2008-2009 Teluu Inc. (http://www.teluu.com)
- Pjsip (See The PJSIP.ORG website)
provides the Open Source, comprehensive, high performance, small 
footprint multimedia communication libraries written in C language 
for building embedded/non-embedded VoIP applications. 

Cryptography notice
This distribution includes cryptographic software. The country 
in which you currently reside may have restrictions on the import,
possession, use, and/or re-export to another country, of 
encryption software. BEFORE using any encryption software, please 
check your country's laws, regulations and policies concerning 
the import, possession, or use, and re-export of encryption 
software, to see if this is permitted.
See <http://www.wassenaar.org/> for more information.

The U.S. Government Department of Commerce, Bureau of Industry and Security 
(BIS), has classified this software as Export Commodity Control Number 
(ECCN) 5D002.C.1, which includes information security software using or 
performing cryptographic functions with asymmetric algorithms. 
The form and manner of this CSipSimple distribution makes it eligible for 
export under the License Exception ENC Technology Software Unrestricted (TSU) 
exception (see the BIS Export Administration Regulations, Section 740.13) 
for both object code and source code.

#### Important
It is important to note that this fork is used for a EU project and most of 
the new features are developed based on the needs for this project. Especially
using Broadcast events to communicate with the client app (see csipsimple-example 
app).

#### Differences from parent repository (https://github.com/r3gis3r/CSipSimple):
 - Gradle build
 - Uses already build native libraries (.so files) from nightly builds
 - Use Broadcast to start calling activity
 - Use Broadcast to send messages
 - Use Broadcast to update an existing account or add a new one
 - Updated design in calling activity
 - Added client app: Standalone app that uses features of CSipSimple using
   broadcast receiver. Currently available features: sending messages, making 
   calls, retrieving CSipSimple version info, updating existing account
