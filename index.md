---
layout: default
title: 三菱PLC + ワイドミュラー u-remote EIP接続方法
description: 三菱PLC（RJ71EIP91）とワイドミュラーのリモートI/O（UR20-FBC-EIP）をEtherNet/IPで接続するための初期設定、IPアドレス設定、Configuration Toolの操作手順を解説した簡易マニュアル。
---

<section style="margin-bottom: 40px; border-left: 4px solid #ffaa00; padding-left: 15px;">
    <h2 style="margin-top: 0; color: #111; font-size: 18px;">1. システム構成概要</h2>
    <p>本ページは、三菱電機製PLC（EtherNet/IPマスタ）と、ワイドミュラー製リモートI/Oシステム「u-remote」（UR20-FBC-EIP）を接続し、データ通信を行うための初期設定手順です。</p>
</section>

<section style="margin-top: 40px; margin-bottom: 40px;">
    <h3 style="color: #444; font-size: 15px; border-bottom: 1px solid #ddd; padding-bottom: 5px;">webサーバの便利機能紹介</h3>
    
    <div style="margin-top: 20px; display: flex; justify-content: center;">
        <div style="position: relative; width: 100%; max-width: 640px; padding-top: 56.25%;">
            <iframe 
                src="https://www.youtube.com/embed/xkDedBbh8ZY" 
                title="YouTube video player" 
                style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0; border-radius: 6px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                allowfullscreen>
            </iframe>
        </div>
    </div>
    <p style="font-size: 12px; color: #666; text-align: center; margin-top: 10px;">PLCやセンサ無しでも、多くのシミュレーションが可能です。</p>
</section>

<section style="margin-top: 40px; margin-bottom: 40px;">
    <h3 style="color: #444; font-size: 15px; border-bottom: 1px solid #ddd; padding-bottom: 5px;">各種設定項目について</h3>
    
    <div style="margin-top: 20px; display: flex; justify-content: center;">
        <div style="position: relative; width: 100%; max-width: 640px; padding-top: 56.25%;">
            <iframe 
                src="https://www.youtube.com/embed/63_66pztw-E"
                title="YouTube video player" 
                style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0; border-radius: 6px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                allowfullscreen>
            </iframe>
        </div>
    </div>
    <p style="font-size: 12px; color: #666; text-align: center; margin-top: 10px;">設定が必要なのは、主にアナログ信号種別等です。</p>
</section>
