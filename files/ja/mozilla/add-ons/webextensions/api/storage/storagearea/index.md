---
title: storage.StorageArea
slug: Mozilla/Add-ons/WebExtensions/API/storage/StorageArea
translation_of: Mozilla/Add-ons/WebExtensions/API/storage/StorageArea
---
<div>{{AddonSidebar()}}</div>

<p>StorageArea はストレージ領域を表すオブジェクトです。</p>

<h2 id="型">型</h2>

<p>StorageAreaはオブジェクト型です。</p>

<h2 id="関数">関数</h2>

<dl>
 <dt>{{WebExtAPIRef("storage.StorageArea.get()")}}</dt>
 <dd>ストレージ領域から1つ以上のアイテムを取得します。</dd>
 <dt>{{WebExtAPIRef("storage.StorageArea.getBytesInUse()")}}</dt>
 <dd>ストレージ領域に格納されている1つ以上のアイテムで使用されているストレージサイズ(バイト単位)を取得します。</dd>
 <dt>{{WebExtAPIRef("storage.StorageArea.set()")}}</dt>
 <dd>1つ以上のアイテムをストレージ領域に保存します。既にアイテムが存在する場合は値が上書きされます。</dd>
 <dt>{{WebExtAPIRef("storage.StorageArea.remove()")}}</dt>
 <dd>1つ以上のアイテムをストレージ領域から削除します。</dd>
 <dt>{{WebExtAPIRef("storage.StorageArea.clear()")}}</dt>
 <dd>全てのアイテムをストレージ領域から削除します。</dd>
</dl>

<h2 id="ブラウザ実装状況">ブラウザ実装状況</h2>

<p>{{Compat("webextensions.api.storage.StorageArea")}}</p>

<p>{{WebExtExamples}}</p>

<div class="note"><strong>謝辞</strong>

<p>このAPIはChromium <a href="https://developer.chrome.com/extensions/storage#type-StorageArea"><code>chrome.storage</code></a> APIに模度づいています。また、このドキュメントは <a href="https://chromium.googlesource.com/chromium/src/+/master/extensions/common/api/storage.json"><code>storage.json</code></a> におけるChromiumのコードに基づいています。</p>

<p>Microsoft Edge での実装状況はMicrosoft Corporation から提供されたものであり、ここでは Creative Commons Attribution 3.0 United States Licenseに従っています。</p>
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