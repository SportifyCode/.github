<p align="center">
  <img src="https://github.com/SportifyCode.png?size=140" width="120" alt="Sportify" />
</p>

<h1 align="center">Sportify</h1>

<p align="center"><strong>Your club in one place.</strong></p>

<p align="center">
  <a href="https://apps.apple.com/app/id6754018526"><img src="https://img.shields.io/badge/App_Store-Download-000000?style=for-the-badge&logo=apple&logoColor=white" alt="App Store" /></a>
  <a href="https://play.google.com/store/apps/details?id=com.unidos.sportify"><img src="https://img.shields.io/badge/Google_Play-Download-000000?style=for-the-badge&logo=googleplay&logoColor=white" alt="Google Play" /></a>
  <a href="https://sportify-app.com/en/"><img src="https://img.shields.io/badge/sportify--app.com-Website-1A6FA3?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/company/sportify-mobile-app"><img src="https://img.shields.io/badge/LinkedIn-Sportify-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://www.instagram.com/sportify__app"><img src="https://img.shields.io/badge/Instagram-@sportify__app-E4405F?style=flat-square&logo=instagram&logoColor=white" alt="Instagram" /></a>
  <a href="mailto:contact@sportify-app.com"><img src="https://img.shields.io/badge/Email-contact@sportify--app.com-333333?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<br/>

Sportify is a **free sports club management platform** that connects ticketing, memberships, academy payments, communication and reporting. Clubs run their operations from one web dashboard; fans, members and parents get everything on their phone.

```mermaid
flowchart LR
  subgraph Fans["📱  Fans · members · parents"]
    APP["Sportify app<br/>iOS · Android"]
  end
  subgraph Platform["☁️  Sportify platform"]
    direction TB
    T["🎟️ Ticketing & season tickets"]
    M["🪪 Memberships & digital cards"]
    Y["🎓 Youth academy"]
    D["💚 Donations & fundraising"]
    C["🔔 Communication"]
    R["📊 Reporting"]
  end
  subgraph Clubs["🏟️  Clubs"]
    direction TB
    W["Club dashboard"]
    B["Box office"]
    S["Web ticketing"]
  end
  APP <--> Platform
  Platform <--> W
  Platform <--> B
  Platform <--> S
```

## ⚽ What we build

<table>
  <tr>
    <th align="left">📱 For fans, members and parents</th>
    <th align="left">🏟️ For clubs</th>
  </tr>
  <tr>
    <td valign="top">
      <ul>
        <li>🎟️ Match tickets and season tickets with QR codes and assigned seating</li>
        <li>🪪 Club memberships with renewals and cards for Apple Wallet and Google Wallet</li>
        <li>💚 Donations and fundraising campaigns</li>
        <li>🎓 Youth academy: enrolment, schedules and fee payments</li>
        <li>🔔 Event accreditations, club news and push notifications</li>
      </ul>
    </td>
    <td valign="top">
      <ul>
        <li>🎟️ Ticketing, season tickets and box office with reserved seating</li>
        <li>🪪 Membership management with renewal tracking</li>
        <li>🎓 Academy administration and fee collection</li>
        <li>📣 Communication tools and push campaigns</li>
        <li>📊 Reporting and financial overviews</li>
      </ul>
    </td>
  </tr>
</table>

> [!TIP]
> Fans never queue again: buy in the app, scan at the gate, keep the season ticket and membership card in your wallet.

## 🤝 Who runs on Sportify

<p align="center">
  <strong>HNK Rijeka</strong> &nbsp;·&nbsp; <strong>NK Varaždin</strong> &nbsp;·&nbsp; <strong>HNK Gorica</strong> &nbsp;·&nbsp; <strong>NK Rudeš</strong> &nbsp;·&nbsp; <strong>NK Croatia Zmijavci</strong> &nbsp;·&nbsp; <strong>NK Karlovac 1919</strong>
</p>

<p align="center"><sub>… and more clubs across Croatia.</sub></p>

## 🚀 A match day with Sportify

1. **Tickets go on sale** in the app and on the club's web shop; members get their priority window first.
2. **Fans buy in seconds**: reserved seat or general admission, card, Apple Pay or Google Pay.
3. **At the gate**, the QR code is scanned; season tickets and memberships live in the phone's wallet.
4. **The club sees everything** in one dashboard: sales, attendance, members, academy fees, donations.

<details>
<summary>🛠️ <strong>Under the hood</strong></summary>
<br/>

| Layer | Stack |
| --- | --- |
| Mobile app | React Native · Expo · TypeScript |
| Club dashboard, box office, web ticketing | Angular · TypeScript |
| Backend | Java · Spring · AWS |
| Payments | Revolut (card, Apple Pay, Google Pay) |

</details>

> [!NOTE]
> Our product code lives in private repositories. For partnerships, integrations or club onboarding, write to [contact@sportify-app.com](mailto:contact@sportify-app.com).

<br/>

<p align="center">
  <sub>Made with ❤️ in Zagreb by <strong>Unidos Grupa d.o.o.</strong></sub>
</p>
