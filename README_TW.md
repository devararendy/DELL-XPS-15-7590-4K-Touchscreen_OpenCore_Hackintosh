 ## XPS 15 7590 4K 觸摸屏 Opencore 黑蘋果

 中文/[English](README.md)

 **OpenCore 版本** : [0.5.8](https://github.com/acidanthera/OpenCorePkg/releases)

 **macOS 版本** : macOS Catalina 10.15.3(19D76) ～ macOS Catalina 10.15.5(19F101)

 ### 經過測試的硬體配置

 | Key                    | Value                                                        |
 | ---------------------- | ------------------------------------------------------------ |
 | 處理器                  | 9th Generation Intel Core i7-9750h                           |
 | 內置圖形處理器           |Intel Graphics UHD 630                                        |
 | 內置觸摸屏幕             | 15.6" 4K UHD (3840 x 2160) InfinityEdge touch IPS            |
 | 記憶體                 | SK Hynix HMA81GS6JJR8N 8G x 2                                |
 | 固態硬碟                | KXG60ZNV1T02 NVMe TOSHIBA 1024GB                             |
 | 聲卡                  | Realtek ALC298                                               |
 | 無線網卡               | 戴爾DW1820A＿BCM94350ZAE 或 聯想DW1560＿BCM94352Z (更換)        |
 ### 使用體驗
 * 非常省電。
 * 使用電池時，功耗不大的使用，例：看影片．文書作業，風扇會停止從而達到省電目的，並且可以保持在非常低溫狀態，不發熱！
 * 盒蓋睡眠期間幾乎完全不掉電。
 ### 工作

 * Intel圖形處理器：工作正常。
 * 無線網卡(**DW1560 or DW1820A**)：「WiFi」和「藍芽」工作正常。
 * 觸摸屏幕：工作正常。
 * 聲卡：「揚聲器」和「麥克風」工作正常。
 * 攝像頭：工作正常。
 * 輸入：「鍵盤」和「觸摸板」工作正常。
 * HDMI接口：熱插拔在v0.5.5後失效
 * USB接口：Type-A port x 2 (Max 5 Gbps) and Type-C port x 1 (Max 10 Gbps)
 * 背光調整：工作正常。
 * 睡眠／喚醒：工作正常。
 * 讀卡機：不工作。
 * 指紋辨識：不工作。

 ### 已知問題

 1. HDMI熱差拔
    * 問題
    
    開機後，第一次接上外接屏幕，正常顯示輸出，拔掉重新接上後，不正常顯示輸出，只顯示鼠標。
    
    * 解決方式
    
    將內置屏幕蓋上１秒再打開，便會看到外接屏幕正常顯示輸出。
    
    

 ### 未經測試

 1. USB Type-C 擴展設備

 ## 歸功於

 - 感謝 、[xxxzc](https://github.com/xxxzc/xps15-9570-macos)
