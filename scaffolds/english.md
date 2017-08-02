---
title: {{ title }}
date: {{ date }}
categories: [English]
tags: 
password: Kevin
abstract: Welcome to my blog, enter password to read.
message: Welcome to my blog, enter password to read.
template:
        <div id="security">
            <div>
                <div class="input-group">
                    <input type="text" class="form-control" aria-label="enter the password" id="pass"/>
                    <div class="input-group-btn">
                        <button type="button" class="btn btn-default" onclick="decryptAES()">解密</button>
                    </div>
                </div>
            </div>
        </div>
        <div id="encrypt-blog" style="display:none">
            {{content}}
        </div>
---
