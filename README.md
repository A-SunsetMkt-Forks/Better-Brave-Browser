# Better Brave Browser  Preview
![image](https://github.com/user-attachments/assets/f61dedeb-80f5-4742-bef1-6a69087b3a2d)


# Synopsis


### Tired of having crypto in your browser? Tired of preinstalled ads in a browser? Tired of the AI features and prefer a 'legacy' browsing experience? Look no further—remove all the garbage: crypto scams, ads, AI chatbots from the Brave browser.


## Appearance Settings

Show old homepage (chromes): brave://new-tab-page/

![image](https://github.com/user-attachments/assets/454036d3-a101-4d9a-aac1-bf9b917aa1af)


![image](https://github.com/user-attachments/assets/ce502c25-43a7-4969-8d7e-7baf8c3bd6b3)

Update: Please make sure new tab page shows is set to home page.


## Data collection (Under Privacy and settings)

![image](https://github.com/user-attachments/assets/05f94aed-d9ae-4fef-b589-bd222f6103c0)

## Windows registry

If you're using Windows, you can achieve even better results than the ones obtained by applying the section [Brave Flags](#brave-flags).

If you're not using Brave on Windows, please skip this section and go to [Brave Flags](#brave-flags).

### How to create the registry file

1. Close Brave Browser if opened

2. Create a txt file wherever you want. For example, you create a file in your Desktop called `brave_debloater.txt`

3. Open the file and paste the content below

```reg
Windows Registry Editor Version 5.00
[HKEY_LOCAL_MACHINE\Software\Policies\BraveSoftware\Brave]
"BraveRewardsDisabled"=dword:00000001
"BraveWalletDisabled"=dword:00000001
"BraveVPNDisabled"=dword:00000001
"BraveAIChatEnabled"=dword:00000000
```

4. Save the file and change its extension to `.reg`. We named the file `brave_debloater.txt` so we will change it to `brave_debloater.reg`

5. Execute and click yes when asked.

## Brave Flags
### Type this in the url bar: brave://flags/

![image](https://github.com/user-attachments/assets/15763528-b20b-4ba1-aa3e-5fd0e99c1106)

### Now this in the menu search each of the following in the flags bar and disable them:

Flags list (Disable them):

![image](https://github.com/user-attachments/assets/d39d10d2-5c3c-42c5-b6ac-90b4aafc3478)

Updated 1/20/25
- #brave-super-referral
- #brave-rewards-allow-self-custody-providers
- #brave-ads-should-always-run-brave-ads-service
- #brave-ads-should-support-search-result-ads
- #brave-ads-allowed-to-fallback-to-custom-push-notification-ads
- #brave-wallet-bitcoin
- #brave-wallet-zcash
- #brave-rewards-gemini
- #brave-ai-chat
- #brave-ai-chat-context-menu-rewrite-in-place
- #brave-cosmetic-filtering-sync-load
- #brave-ai-chat-open-leo-from-brave-search
- #native-brave-wallet
- #brave-news-peek
- #brave-news-feed-update
- #brave-rewards-platform-creator-detection

## uBlock filters:

### Copy all the lists and add them to custom filtering lists.
### Note: Brave does some wierd whitelisting thing so some ads might not get blocked even though it's in a block list.

![image](https://github.com/user-attachments/assets/ad43d99c-c330-47e1-8593-54b6de5a2d29)


![image](https://github.com/user-attachments/assets/3810ed7f-811b-43c7-927d-d0503af18155)

## Links (They are hyper linked copy them by right clicking)
- Ads: [uBlock Ads](https://raw.githubusercontent.com/uBlockOrigin/uAssets/refs/heads/master/filters/filters.txt)  
- Privacy: [uBlock Privacy](https://raw.githubusercontent.com/uBlockOrigin/uAssets/refs/heads/master/filters/privacy.txt)  
- Quick fixes: [uBlock Quick Fixes](https://raw.githubusercontent.com/uBlockOrigin/uAssets/refs/heads/master/filters/quick-fixes.txt)  
- Unbreak: [uBlock Unbreak](https://raw.githubusercontent.com/uBlockOrigin/uAssets/refs/heads/master/filters/unbreak.txt)  
- Badware: [uBlock Badware](https://raw.githubusercontent.com/uBlockOrigin/uAssets/refs/heads/master/filters/badware.txt)  

### Adguard Filters:

- Adguard: [Adguard Base](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_Base/filter.txt)  
- Adguard Tracking Protection: [Adguard Tracking](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_3_Spyware/filter.txt)  
- Adguard Annoyance: [Adguard Annoyances](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt)  

### Easylist:

- Easylist: [Easylist](https://easylist.to/easylist/easylist.txt)  
- Easylist Privacy: [Easylist Privacy](https://easylist.to/easylist/easyprivacy.txt)  
- Easylist Cookies: [Easylist Cookies](https://secure.fanboy.co.nz/fanboy-cookiemonster.txt)  

### Malware / Phising:

- [Malware Filter](https://malware-filter.gitlab.io/malware-filter/urlhaus-filter.txt)  
- [Phishing Filter](https://malware-filter.gitlab.io/malware-filter/phishing-filter.txt)




