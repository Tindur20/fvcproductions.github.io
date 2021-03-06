---
title: "Sort Detective - Solution"
date: 2015-04-18
description: "Stuck on that homework assignment involving SortDetective.jar? No need to worry! ☕"
image: https://i.imgur.com/aNVfqmh.jpg
aliases:
  - /2015/04/18/sort-detective-solution/
categories:
  - blog
---

> This tutorial is "certifiably" Mac Friendly. Whoop. 

## Files Provided To You

- `SortDetective.jar`, which looks something like this:

![Sort Detective 1](https://lh3.googleusercontent.com/XsFzEY2Cyjw2RbXq-PWhqdQ6_SyGWg-UEf2kyyySakAE-mbSuhV5Sp-pyljRU-h0hbb3negRAcqig5F9gP6TGbMgwT1DfYmHIjBu8BlEZMD2mXgogw-I2S37qjY7kUnA_QxRNzNrnq0jFnJl1fnObc_48PblUOMEv3PCICJ0wxS-VZnLcX_M8B5RKPKIg0fc2hFbWYgVlU3idhzLBsHn-FYpFeF3-lI6bR_7nrfRENNmaBdEOrQRtNHrNFu4q-eNVsXgSEzOP8Fqn46asxICdh035LHhtWEqEWUhs2K-orQltMjJC1d7RaFkYuLLNlTYOJHxNwkO3vOtTwmnXiKgiMP_8gqcUMa9Q2o4f-rp2CHB5Ykx2mZntThtuJcTqGmMKG_WHcju7PNtYyEAJ_I9DQajpdWWnVSKTldUmH8rW8K6naXzFg7_ktTMXiTu_yomPVfGMg8ADBKXWRDDPcdSJPsbQQ2MCFOEocqepSvSSVd17RJaAFEArky4lidsIgAuKOtX7a596Pt3Msaj9PxbUSpLhIXHmMxsF0q2xIa1tYIPdDnnfV6H5nrApLFBHJ3MqNAxqLt3mzZEviofUao3Y6-lRmjExtXgFaQQfDZHKh0TSae5uNy9SYGsFej1yyzy=w503-h531-no)

> The purpose of this little HW assignment is to correctly identify the 6 Greek letters (Alpha, Beta, Gamma, Delta, Epsilon, & Zeta) with their matching sorting method (selection, insertion, bubble, quick, merge, & heap sort).

## Step 1 - Download JD-GUI

Head over to the Java Decompiler [page located at `jd.benow.ca`](https://jd.benow.ca/ "Java Decompiler")) and download the `ZIP` file for the `JD-GUI`.

![Sort Detective 2](https://lh3.googleusercontent.com/rmpHtmddoL95gbLfiF7jPJDUcn-I3I48hWRsYuFvzIjUn0YNHuAr2JgsyGA_xvilBUX8cg31gbjx25xbDnq-8o4Wb3FII5Fk6y0ieIzGCZ1sNpio254-8QKqRJE3E_oxi0C4iGVKRtJZWR0LxlQ-b6FQmKIPLGPJQiMAWKAb1d81Zd0lj-LROXoVfoCZs-Hakg9K_lz0_p6nRtFlBujamS25qiCrx6UYfJBAtvBpOzqVHaduwWkaEYCr0UA_q3Rk-9AoqA0UpZVGgRScQpmQ8ZNdVVnVgWvI1aCODTXaHkU_Sn-6_xR1K98Aaq0f44LHzgpiGs5Hay7jcs-_f2M95n7KAAHajDimrJ4BFEsxCDhxfIVuQ3A0gDQtYwLljlF91VhhjL5eQK-25wtIfKAgDXu7uySDr3h7JrLq0CbnAz-_mUiZWC_XO-cpODAh521yXGLZ4T5Ua4ZqQcy8SCPlww9UyeomZ_wsBmcXeaVxJU8rZwyKotwFIoib_qplsSvPTNh6RH_lNmzxGJhDzs-HIhuRj_id38aRDMJLS4J0pxTeUfExN69KweQwSi8w40CnpB0YbHCeQOgA47MpISV_TMIufaqIyRpeswBYjMFBVjXxgJd1JU6SGpkD4yZFqmOW=w1323-h725-no)

## Step 2 - Launch JD-GUI

Now that you've downloaded the `ZIP` file, unzip it and launch the application.

![Sort Detective 3](https://lh3.googleusercontent.com/JED5qNDsZkRRitD7eaETeo_0vOhVfKVEAeUNr2d1bE0aSztEznJPaApdn1W9h00WF-iufwUuwCs7tFyijhGZEKBXpxXIezagHHnIqxOSfSyygSIB_2EawAoqrjXJxM4XXqPNrKOGbZ8X0BMvEqf36KHgeX-RjvROvWWlBwg5JguuzXU_slMukbQssEmiTFUeZxBcGwsRVD9Ro07ToiKnEpb1WqudFSEEPoo_F1RL-S2pwo3ODqQqRQtSjU7OBbv-XZuXb2LueTix3ldvR8-ZiZrevXBuJ5KxPzubPeJ2U9Yx3KGP8EQuWSFAA6HpzfUKg_UTDaM3CqtDnTihgpthTLsMF4hkAWYYMsn2iV_APY0HdkkyKPpkfs9VFeyL2fcRu2V3g-f_BG7Fg0uQgZ5oof2hPZhIcyw6yGrYPpUPO1N4h892VJgEL2DwZgc8bN6rwEdo3e7QudRQQP69xjVvXVO3Hpx-BKndkpXS_TTwGNw5crbJI-5U-HLBMXDmeH_M9BaSt6s9HJVSZu_D_-l9ZPedZQpET83-2IufoX_IFqJeKrovMgdL_FWp5OOrub5RN3RddxlTrgkpk1jDl3wy2gebUCUp2KGihag1D6kTUL-IUo0Wo_9nx-x2MdeVLp5n=w825-h792-no)

## Step 3 - Open your `SortDetective.jar` file using `JD-GUI`

![Sort Detective 4](https://lh3.googleusercontent.com/TUul6pXsISvcQ0LdZEnR004V-83nJtIwtoUH-tAu7yCriGshaTQ_MgZEnmFvMEDXIVljsUQS1xKy7igsDkOFOOJDV7lvMmksPfKHz3IWNKelzuw66ssMdpopcq2axEltboYzh6jwbmHEFtaOPtygXpEBbyxhE7bpWpIx1xZNxS9N8oXUip7CV07CyxZ09_q8qePOtBYYGfpabt-8u43BAop7y_S7M9HLMjyOUfKGYQqf2kpCAWi2C6HFg8v9DgIixPvtKs7ZUOVfQiLaPY6PDE1M89t6ME5Eoql6V7GZT6w60Ds3uxEskkSSSp7kpOV4Z1zs59HVkQRihiYK51QgvX8pTzE6gwHrtCiqbLM9ljjLYEx1RrhOH27ffW79S7kKWeSAFeFnO3pZrZ2sYy2w0q7lKpw9Qny-odfnzSRWzZw-ZT7bnCgf1r3vt3Itay9sqmG_gbT3Tt9VXbIUyCh4_cGTUBLW1Uj37uZ1gWquzxVf1zIFvDkKPJ2dOKN5U5UaK07NJhmwqdm4OqPzJXQEF7Vf9QBKHgJHXoL4DmB83FCWi4_PlbEl3Deyhhd5yO53sqk5MF3vInbf6OmsGHjpsEpBx_1DicMHh6TP_rpouRPK768opRdWDFkfDCUCDhP6=w700-h691-no)

# Step 4 - Find the Formula That Determines The Order

`SortDetective.jar` determines the sorting method ordering according to your student ID.

It has an array defined with **5 different** orders that the sorting methods **CAN** be placed in. See `Line 256` in the `SortDetective.class`.

![Sort Detective 5](https://lh3.googleusercontent.com/iLkixqWEJHZbwt_JRkrGh1ltBwn3BGoqJR385o69HPyhalSQTfNHuRpWY7_8s2dlEQLyKIaMY__Bfx2F8y-M92MXt-484lncbW3vvILveJwUorG3XgRWzsQvm5PZ9TMa6X6RrYGWHJVEvIxPbWndbAP3PscNXSGAzm787UJaYkpG0KHYT76k_L1JSaSWqBcV_5bY_nPZaplqfq5zEhvY1SJ8LI_iJrQm548a13-rSdcAgCI_iPCGmOjCUGEMR3lMLSAKgqDZeTy-a5MlRKfUJMDQ1xvK__JKH7ZqLzxAY1CNAsmO8-hG2EyRIUxycOUevZzP2Nu5vbpoRp1EQQPA0SIEIDV0uYLtB_jEbnbqryZSGYDkkQmyP4kJF-6k72IDARUeny7QrDHxkJOpkwsEn25KTwH6So11G_HUsOPHkaW5MF1QuN-GMPTsutOKXAl_mgs56KKeVkeesvAP8fp_xh6eGZmOcYbOgBURYO1A5ZqOJk20pPE9hJup-1upaYyoDMOOa3IC1uKltYRbjwnl_ixqUXRQzPhJ8hgkMa1nxpKhfMxK7YoW6MPjH8lveB47MHN5KK_ldvBMrQWOKp8ALisFaCxqUG4k1qQz1qFoIYXZTXJwqBVHa18-WHmBdlQQ=w365-h220-no)

Zooming in...

![Sort Detective 6](https://lh3.googleusercontent.com/4M0ejbY55jA-9YmQaaGX16Z2hOX4zTC0dN1h6oM9M8bDEcCb6LdG_6KXHKCa3heNlQe8TYGFEFclN04uHV8lLu-lgWR2SF8c-HDIIocra64Jt3MNHafda85EQaQEi_vAs_ZuwKqM-MYlZFbkIAZRGnwNs4nwi5wjARsrokMcwznqizNaowpKL-IZfp7bZ1pxh1ANZ0WsPDqBvVISBHYsFqrBVm8nN0gNuqTBYC-0AVR7DPjzRWQ2yXBYsDCEHU8IVNdys4Y1C_9s6Kg_nVuPCenVf_0g9xuOOZfigamtCKNP_yUZB3pdT1vhRPBDWxpDs9RGQYQnPsvWm96Zkrrd4spPHKWXkBKw2JS5QtYiCzUdrKBdHDmO2RRA5Hv8s25x8ZCi8e8uuqcfGtGOHez8f_Ixq9yTyNnIG8ogjUX114MiRO9uSx309bmD0hZ7fT9rqWvGvauVjwcmfcSqKkuP9IET-e9OT096-cI_1Lz8OMF1CNMZ39dtdgcDx1r-oToe-Zx5wFU9C4h10u6tj98CQiatnC2rHW8BkX5x5f5N7_PQkd9CxS_WPt-8ynAyLlptC9oysJyTWdnUuIXB_2odZ3Z1pw-mWRMcIunU3d8yhShFJUgOJjZuSxF8mjkL4NMp=w1280-h378-no)

With some minor searches, we find out that the method `experimentOrders` uses the variable `selectedPermutation` to determine what array value it will use to determine the order.

![Sort Detective 7](https://lh3.googleusercontent.com/RFj55ZV2Z2Sjl4DODl7gmeAXRcrJgVhjidxJdiuPPg_G5AySmdAJA0FXOKK1iFA4ZmD1DrdfVaRKk69ZCfw2iG2SlKi5mG8BzUhCOsQ_Og6ntI--j8IdMF1RvUJyOmu9IZlitiGKPUQRzlFxP0KbIzV25bCeriFugoLtq8nehqv81V5ea49v2r_gVwT7Xr8k58Ijmj7RbkMsOnIAMlDa53l8EmyBv15cXLz4UYt2qNGOtUNobFwi1cQooFvCS0EZfsLxbIH8nztH8AGhOfPujMeTKVp9lwPIJt0ltdrTpe4nWcaM1zIXLD081T7UG7Rb-HGJOWjgp5sAedEnZ4C5ZemthwyLZRGA1nJpQxxtiZ-C-I2fyZKxS8vekn3FCfJ4a7VY0GJVyPEvxYgYcGVn8EONaXDz5LNkqKGmUFPqqLRM5DjXGHVL958iQb0I1NLRB4ZfTp8RlMUXVx34JMlKGGHuSYP1LM-2N3vYGVHNjAr5DYdOt5memP6tfss-ls0iS-T6RQJlAcMGl8Krl7h6ejL4-V4kFjKrv1lbdDtpzDX01fiqMXmK2Zf8SEAq3CGMKJqz22zncGvLOZ7BCCCCeUdNIT1LtaJS8MDzyn25vt5Jzpjzlv7nXd6uxHtseTXe=w573-h109-no)

This redirects us to the `setStudentID()` method. So now we've figured out the ordering all just depends on the formula the program uses.

![Sort Detective 8](https://lh3.googleusercontent.com/dDyAo6rZcql-vBny5qAWI-v-xXXEgRYpUiwVm40zDF6-1J8j_1KAtpU_xdW-h75POqxGzF4NBIl5Nw5EQif2z8megSu2msB8T3GWPmG7FcEXTbyPOsPfCgNgFAzfWpHvOsIk-3NsScMWa2SE4WXX1Geu3iORGvGRMQ6v3M4tHqCqxGD_bktvMbrrr1bl1C7v0BsQ-YsLZVSRth6v-s3MVVIgQuKkYmJ5Am3MUjqawgT3yfE_a3xKT3L3O45Yg54z6thDzpODB11SQwoyJFzcVs-FBuJ-fIMadU0qx1_cBCBt9i-tBr90J2U-ssDu9QsPsggNAZnpxwCFGih08NysAT_t0NV4yRaapbSqlZ4GVxRpADDburmIVrJkN1novo4Q5vt-dRbaFypzODdsNIU_J5MV4M2ueB5UlTdN7nlMpIv6UAYXGc5bQmoK4ZW9REGLM-wHky8PylR1NC9vVbQFTyzFBgyFQjeA6zA3-I5EzfRjkeo7WnbrjIxtT-kgPJv1OqdESKgLaKABVgW3JD-VJ3wdVhG4XVu4va01rSifO29rKazOpTmuhQUNmtKwSqMfNxpLl85WGmaeDtMHOFg1dFKY_smhK79mmoOFSdRijFnW9U3tBP7EbqPD55W9gmN4=s800)

## Step 5 - Apply Formula To `experimentOrders`

So, in my case, my student ID is `00319124`.

Using the formula, we can determine that the value of `selectedPermutation` is going to be `2` for me since `319124` / `10` % `5`= `2.4` or simply `2` for `int`. That means that the array value for `experimentOrders` will be `2`, making a match to the order found on `Line 7` when zooming in to `Line 256` in `SortDetective.class`.

Remember, arrays are ordered like `{0,1,2}`. So `experimentOrders[2]` would be the 3rd value in the array.

![Sort Detective 9](https://lh3.googleusercontent.com/4M0ejbY55jA-9YmQaaGX16Z2hOX4zTC0dN1h6oM9M8bDEcCb6LdG_6KXHKCa3heNlQe8TYGFEFclN04uHV8lLu-lgWR2SF8c-HDIIocra64Jt3MNHafda85EQaQEi_vAs_ZuwKqM-MYlZFbkIAZRGnwNs4nwi5wjARsrokMcwznqizNaowpKL-IZfp7bZ1pxh1ANZ0WsPDqBvVISBHYsFqrBVm8nN0gNuqTBYC-0AVR7DPjzRWQ2yXBYsDCEHU8IVNdys4Y1C_9s6Kg_nVuPCenVf_0g9xuOOZfigamtCKNP_yUZB3pdT1vhRPBDWxpDs9RGQYQnPsvWm96Zkrrd4spPHKWXkBKw2JS5QtYiCzUdrKBdHDmO2RRA5Hv8s25x8ZCi8e8uuqcfGtGOHez8f_Ixq9yTyNnIG8ogjUX114MiRO9uSx309bmD0hZ7fT9rqWvGvauVjwcmfcSqKkuP9IET-e9OT096-cI_1Lz8OMF1CNMZ39dtdgcDx1r-oToe-Zx5wFU9C4h10u6tj98CQiatnC2rHW8BkX5x5f5N7_PQkd9CxS_WPt-8ynAyLlptC9oysJyTWdnUuIXB_2odZ3Z1pw-mWRMcIunU3d8yhShFJUgOJjZuSxF8mjkL4NMp=w1280-h378-no)

There we go! Just like that, I now know for sure that the ordering of the Greek letters for me would go

- Alpha - Quick Sort
- Beta - Selection Sort
- Gamma - Merge Sort
- Delta - Bubble Sort
- Epsilon - Insertion Sort
- Zeta - Heap Sort

### Good luck with your HW! :wink:
