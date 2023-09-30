



# Update

https://github.com/fr303388/iceriver_oc_cht/releases/download/KS0_web/update.bgz

KS0請使用WebUI執行更新韌體後，重開機可正常超頻160G







=================================== OLD DATA ============================================

# iceriver_oc_cht

1. 事前準備
   
   1. 100W以上電原，100W可以超頻至160G。請注意不要接在UPS不斷電後面，超頻容易受到限制。
   2. 下載更改過的超頻設定檔案 [https://https//github.com/fr303388/iceriver_oc_cht/releases/download/KS0/iceriver_oc.7z](https://github.com/fr303388/iceriver_oc_cht/releases/download/KS0/iceriver_oc.7z)
   3. 下載並安裝 eclipse https://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/2023-09/Reclipse-java-2023-09-R-win32-x86_64.zip&r=1
   4. 啟動eclipse
   5. 前往上面的標籤 Help -> Install new Software

  ![螢幕擷取畫面 2023-09-30 130523](https://github.com/fr303388/iceriver_oc_cht/assets/18081508/3d432df6-460c-4a46-aef9-1da6bc68e301)


   6. 輸入以下網址下載它: https://download.eclipse.org/tools/tcf/releases/1.7/1.7.0

  ![螢幕擷取畫面 2023-09-30 132856](https://github.com/fr303388/iceriver_oc_cht/assets/18081508/331f1e67-98a4-4640-889a-9f96bb99f8a5)

   7. 點選新增，隨意取個名稱
   8. 選擇“"Target Communication Framework”和“TCF Target Explorer”
   9. 點擊下一步並同意許可，點擊完成
   10. 出現提示時重新啟動 eclipse
   11. 當 eclipse 沿著頂部欄重新啟動時，應該有一個「新連接」的新選項
       
       ![螢幕擷取畫面 2023-09-30 132642](https://github.com/fr303388/iceriver_oc_cht/assets/18081508/8e63b5af-7921-4565-91e1-3c8eb88bfa0a)
       
   13. 輸入IP登入礦機系統

       ![螢幕擷取畫面 2023-09-30 132954](https://github.com/fr303388/iceriver_oc_cht/assets/18081508/e44e7609-4a6f-4a52-b651-5e13a6b8eede)
       
   15. 登入成功候選下面的SYSTEM FILE.
       
   .
      ![螢幕擷取畫面 2023-09-30 133107](https://github.com/fr303388/iceriver_oc_cht/assets/18081508/51c5ecb0-2e6c-42ae-8226-de3b8241c32f)



  17. 修改檔案權限可寫入，否則無法改名

  ![螢幕擷取畫面 2023-09-30 133635](https://github.com/fr303388/iceriver_oc_cht/assets/18081508/7ed63a4d-5923-407e-8789-565cd193e784)
  

  18. 更改/etc/shadow檔案為 shadow_
  19. 更改/etc/sudoers檔案為 sudoers_
  20. 把更改過的檔案移至"資料夾"，請勿直接拉到根目錄，會有錯誤!!

  ![螢幕擷取畫面 2023-09-30 133904](https://github.com/fr303388/iceriver_oc_cht/assets/18081508/de495291-c3b2-433e-a625-2cbeaa0bf401)


  22. 刪除/var/update/miner.bgz，如沒有請刪除0627_v1_ks0miner.bgz
  23. 0627_ks0bg.bgz請勿刪除，否則無法正常登入網頁礦機

  ![螢幕擷取畫面 2023-09-30 133729](https://github.com/fr303388/iceriver_oc_cht/assets/18081508/dc082701-efa2-41b0-abee-95b2bf09a74f)

  24. 加入更改過的miner.bgz
  25. 完成，請重開機後觀察。
      
如本文對您有幫助，請贊助 謝謝您

kaspa:qzal8fx9yjd7exqlmpjcf386vh2h3k324kdsf4pqhd82l4xrlnpuzcwhh6glc








   
