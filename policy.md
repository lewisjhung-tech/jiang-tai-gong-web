# Privacy Policy — Lewis Creator Agency TikTok Content Posting Service

> 取代 ~/automation/tiktok_bot/privacy_policy_draft.md（個人 owner 版作廢）
> > 用途：TikTok Content Posting API audit 必要的 agency 隱私政策公開網頁
> > > 待 Lewis 填：Lewis Creator Agency / lewisjhung@gmail.com / 2026-06-25 / 最終公開 URL
> > > > Phase 2 部署到 GitHub Pages 後 URL 給 TikTok audit
> > > >
> > > > **Last updated:** 2026-06-25
> > > >
> > > > ---
> > > >
> > > > ## Who we are
> > > >
> > > > This application ("the Service") is operated by **Lewis Creator Agency** as an authorized agency service. The Service publishes original video content to TikTok on behalf of authenticated creator clients ("Creators") who have explicitly authorized Lewis Creator Agency to manage their TikTok presence.
> > > >
> > > > Operator contact: **lewisjhung@gmail.com**
> > > >
> > > > ## What data we collect
> > > >
> > > > The Service collects and stores only the minimum data required to operate:
> > > >
> > > > ### From Creators (our clients)
> > > > - **TikTok OAuth access token & open ID** of each authorized Creator, obtained when the Creator authorizes the Service through TikTok's official OAuth flow.
> > > > - - **Creator profile basic info** (username, display name, follower count, account type) - retrieved via TikTok's `user.info.basic` scope and stored locally for managing the Creator's posting calendar.
> > > >   - - **Video content** uploaded by Lewis Creator Agency staff to publish on behalf of the Creator.
> > > >    
> > > >     - ### From Lewis Creator Agency staff (internal users)
> > > >     - - Login credentials (email + password hash) for accessing the management dashboard.
> > > >       - - Audit log entries (who scheduled what post for which Creator, at what time).
> > > >        
> > > >         - ### What we DO NOT collect
> > > >         - - We do **NOT** collect data from TikTok users who are not our authorized Creator clients.
> > > >           - - We do **NOT** collect viewers' personal data, browsing history, or analytics from TikTok.
> > > >             - - We do **NOT** scrape, harvest, or process data from any third-party TikTok accounts.
> > > >               - - We do **NOT** use the Service to interact with other users' content (no likes, comments, follows on behalf of Creators).
> > > >                
> > > >                 - ## How we use the data
> > > >                
> > > >                 - OAuth tokens and Creator data are used **exclusively** to:
> > > >                
> > > >                 - 1. Query the authorized Creator's account info (required by TikTok API before posting).
> > > > 2. Upload video files provided by Lewis Creator Agency staff to the authorized Creator's TikTok account.
> > > > 3. 3. Publish those videos via TikTok's Content Posting API.
> > > >    4. 4. Apply the required `branded_content` / `paid_partnership` disclosure toggle on every post (TikTok compliance requirement for agency-published content).
> > > >       5. 5. Track posting status (success / failure / pending) for the Creator's reference.
> > > >          6. 6. Generate audit logs for compliance with TikTok's developer guidelines.
> > > >            
> > > >             7. The Service performs no other action with Creator data and shares it with no one outside Lewis Creator Agency.
> > > >            
> > > >             8. ## Data storage & retention
> > > >            
> > > >             9. - All Creator OAuth tokens and personal data are stored **encrypted at rest** on Lewis Creator Agency's private server, never on public or third-party cloud services.
> > > > - Tokens are retained only as long as the Creator authorizes the Service. Creators can revoke access at any time by:
> > > > -   - Removing the Service in TikTok app: Settings → Manage account access → Apps
> > > >     -   - Or emailing lewisjhung@gmail.com to request immediate deletion
> > > >         - - Upon revocation, all stored tokens and Creator data are deleted within 7 days.
> > > >           - - Audit logs (anonymized after Creator deletion) are retained for 12 months for compliance audits, then deleted.
> > > >            
> > > >             - ## Data sharing
> > > >            
> > > >             - We do **NOT** sell, share, or disclose any Creator data to third parties. The only external services contacted are:
> > > >            
> > > >             - 1. **TikTok's official API** — to perform the posting Lewis Creator Agency requested on behalf of the Creator.
> > > > 2. Standard infrastructure providers (e.g., GitHub Pages for hosting this policy page, no Creator data passes through).
> > > >
> > > > 3. No advertising networks, analytics platforms, or third-party data brokers receive any Creator data.
> > > >
> > > > 4. ## Branded content disclosure
> > > >
> > > > 5. In compliance with TikTok's branded content and creator marketplace policies (TikTok Creator Disclosure rules, April 2026 update):
> > > >
> > > > 6. - Every video published through the Service has the `branded_content` and/or `paid_partnership` toggle applied via the Content Posting API.
> > > >    - - This disclosure is enforced programmatically and cannot be bypassed by Lewis Creator Agency staff.
> > > >      - - Creators retain full visibility of all posts published on their behalf through their own TikTok account dashboard.
> > > >       
> > > >        - ## Creator rights
> > > >       
> > > >        - Each authorized Creator has the right to:
> > > >       
> > > >        - - **Access**: Request a copy of all data Lewis Creator Agency holds about them by emailing lewisjhung@gmail.com.
> > > > - **Correction**: Request correction of inaccurate data.
> > > > - - **Deletion**: Request immediate deletion of all their data (processed within 7 days).
> > > >   - - **Revocation**: Revoke OAuth authorization at any time through TikTok app settings, without prior notice.
> > > >     - - **Audit**: Request a copy of the audit log of posts published on their behalf.
> > > >      
> > > >       - ## Security
> > > >      
> > > >       - - All data transmission uses TLS 1.2+.
> > > >         - - OAuth tokens are encrypted at rest using industry-standard encryption (AES-256).
> > > >           - - Access to the Service's management dashboard is restricted to authorized Lewis Creator Agency staff and protected by 2FA.
> > > >             - - We perform regular security audits and follow TikTok's developer security guidelines.
> > > >              
> > > >               - ## Changes to this policy
> > > >              
> > > >               - We may update this policy as TikTok's API or compliance requirements change. Material changes will be communicated to all authorized Creators by email at least 14 days before taking effect.
> > > >              
> > > >               - ## Compliance
> > > > 
This Service complies with:
- TikTok Developer Terms of Service
- - TikTok Content Posting API Guidelines
  - - TikTok Creator Disclosure rules (April 2026)
    - - Taiwan Personal Data Protection Act (個人資料保護法、適用於台灣 Creator clients)
     
      - ## Contact
     
      - For privacy questions, data deletion requests, or compliance inquiries:
      - - Email: **lewisjhung@gmail.com**
        - - Service operator: **Lewis Creator Agency**
         
          - ---

          *This Privacy Policy is published at https://lewisjhung-tech.github.io/jiang-tai-gong-web/ (Phase 2 GitHub Pages deployment).*
          
