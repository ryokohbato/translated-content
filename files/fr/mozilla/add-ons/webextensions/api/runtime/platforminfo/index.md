---
title: runtime.PlatformInfo
slug: Mozilla/Add-ons/WebExtensions/API/runtime/PlatformInfo
tags:
  - API
  - Add-ons
  - Extensions
  - Non-standard
  - PlatformInfo
  - Reference
  - Type
  - WebExtensions
  - runtime
translation_of: Mozilla/Add-ons/WebExtensions/API/runtime/PlatformInfo
---
<div>{{AddonSidebar()}}</div>

<p>Un objet contenant des informations sur la plate-forme actuelle.</p>

<h2 id="Type">Type</h2>

<p>Les valeurs de ce type sont des objets qui contiennent les propriétés suivantes:</p>

<dl>
 <dt><code>os</code></dt>
 <dd>{{WebExtAPIRef('runtime.PlatformOs')}}. Le système d'exploitation de la plateforme.</dd>
 <dt><code>arch</code></dt>
 <dd>{{WebExtAPIRef('runtime.PlatformArch')}}. L'architecture du processeur de la plateforme.</dd>
 <dt><code>nacl_arch</code></dt>
 <dd>{{WebExtAPIRef('runtime.PlatformNaclArch')}}. L'architecture du client natif Cela peut être différent de <code>arch</code> sur certaines plates-formes.</dd>
</dl>

<h2 id="Compatibilité_du_navigateur">Compatibilité du navigateur</h2>

<p>{{Compat("webextensions.api.runtime.PlatformInfo")}}</p>

<p>{{WebExtExamples}}</p>

<div class="note"><p><strong>Note :</strong></p>

<p>Cette API est basée sur l'API Chromium <a href="https://developer.chrome.com/extensions/runtime#event-onConnect"><code>chrome.runtime</code></a>. Cette documentation est dérivée de <a href="https://chromium.googlesource.com/chromium/src/+/master/extensions/common/api/runtime.json"><code>runtime.json</code></a> dans le code de Chromium code.</p>

<p>Les données de compatibilité relatives à Microsoft Edge sont fournies par Microsoft Corporation et incluses ici sous la licence Creative Commons Attribution 3.0 pour les États-Unis.</p>
</div>

<div class="hidden">
<pre>// Copyright 2015 The Chromium Authors. All rights reserved.
//
// Redistribution and use in source and binary forms, with or without
// modification, are permitted provided that the following conditions are
// met:
//
//    * Redistributions of source code must retain the above copyright
// notice, this list of conditions and the following disclaimer.
//    * Redistributions in binary form must reproduce the above
// copyright notice, this list of conditions and the following disclaimer
// in the documentation and/or other materials provided with the
// distribution.
//    * Neither the name of Google Inc. nor the names of its
// contributors may be used to endorse or promote products derived from
// this software without specific prior written permission.
//
// THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
// "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
// LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
// A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
// OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
// SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
// LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
// DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
// THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
// (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
// OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
</pre>
</div>