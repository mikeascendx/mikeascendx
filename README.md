<!-- markdownlint-disable MD013 MD033 MD041 -->

<p align="center">
  <a href="https://mikeascend.pages.dev">
    <img
      src="./assets/portfolio-hero.png"
      alt="John Mike's developer workspace — visit the portfolio"
      width="100%"
    />
  </a>
</p>

<img width="100%" height="50" src="https://i.imgur.com/dBaSKWF.gif" alt="" />

## Business Web Solutions

<div align="center">
  <table align="center">
    <thead>
      <tr>
        <th>Project</th>
        <th>Type</th>
        <th>Live</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="left">RawLens PH Operations Platform</td>
        <td align="left">Philippines · Business Operations System</td>
        <td align="left">Private · <a href="https://www.instagram.com/rawlensph/">RawLens PH</a></td>
      </tr>
      <tr>
        <td align="left">RawLens PH Customer Portal</td>
        <td align="left">Philippines · Customer Booking Portal</td>
        <td align="left">Private · <a href="https://www.instagram.com/rawlensph/">RawLens PH</a></td>
      </tr>
      <tr>
        <td align="left">Krüershof Digital</td>
        <td align="left">Germany · Web Design Agency</td>
        <td align="left"><a href="https://www.kruershof-digital.de/">kruershof-digital.de</a></td>
      </tr>
      <tr>
        <td align="left">PALA Consulting Group</td>
        <td align="left">Germany · Business Consulting</td>
        <td align="left"><a href="https://palagroup.de">palagroup.de</a></td>
      </tr>
      <tr>
        <td align="left">Pala Realty</td>
        <td align="left">Germany · Real Estate</td>
        <td align="left"><a href="https://pala-real-estate.com">pala-real-estate.com</a></td>
      </tr>
      <tr>
        <td align="left">Smaragdblüte</td>
        <td align="left">Germany · Travel Tech</td>
        <td align="left"><a href="https://www.smaragdbluete.de/">smaragdbluete.de</a></td>
      </tr>
      <tr>
        <td align="left">ARTWussow</td>
        <td align="left">Germany · Art &amp; Gallery</td>
        <td align="left"><a href="https://www.artwussow.de">artwussow.de</a></td>
      </tr>
      <tr>
        <td align="left">Autocenter Mülheim Göksu</td>
        <td align="left">Germany · Automotive Sales &amp; Services</td>
        <td align="left"><a href="https://www.ac-o.de/">ac-o.de</a></td>
      </tr>
      <tr>
        <td align="left">FlashyVendor</td>
        <td align="left">USA · Luxury Jewelry</td>
        <td align="left"><a href="https://flashyvendor.com">flashyvendor.com</a></td>
      </tr>
      <tr>
        <td align="left">Schweriner Goldankauf</td>
        <td align="left">Germany · Gold Buying, Selling &amp; Antiques</td>
        <td align="left"><a href="https://schweriner-goldankauf.de">schweriner-goldankauf.de</a></td>
      </tr>
      <tr>
        <td align="left">Dachdecker Wittler</td>
        <td align="left">Germany · Roofing Services</td>
        <td align="left"><a href="https://www.dachdecker-wittler.de/">dachdecker-wittler.de</a></td>
      </tr>
      <tr>
        <td align="left">Renate Reimann Energiemedizin</td>
        <td align="left">Germany · Health Services</td>
        <td align="left"><a href="https://www.renatereimann.de">renatereimann.de</a></td>
      </tr>
      <tr>
        <td align="left">NP Trucks</td>
        <td align="left">Germany · Automotive Sales &amp; Services</td>
        <td align="left"><a href="https://www.np-trucks.de">np-trucks.de</a></td>
      </tr>
      <tr>
        <td align="left">Dietz Webdesign</td>
        <td align="left">Germany · Web Design Agency</td>
        <td align="left"><a href="https://www.dietz-webdesign.de/">dietz-webdesign.de</a></td>
      </tr>
      <tr>
        <td align="left">Das Gold und Antikhaus</td>
        <td align="left">Germany · Gold Buying, Selling &amp; Antiques</td>
        <td align="left"><a href="https://dasgoldundantikhaus.de">dasgoldundantikhaus.de</a></td>
      </tr>
      <tr>
        <td align="left">Steven Noora</td>
        <td align="left">Philippines · Filmography Portfolio</td>
        <td align="left"><a href="https://stevennoora.pages.dev">stevennoora.pages.dev</a></td>
      </tr>
    </tbody>
  </table>
</div>

```mermaid
flowchart LR
    john["John Mike Asuncion<br/><i>AI Operator · Software Builder</i>"]
    leadupfront["LeadUpFront<br/><i>Philippines · Growth & Business Development Systems Agency</i>"]
    rawlens["RawLens PH<br/><i>Philippines · Photography</i>"]
    kruershof["Krüershof Digital<br/><i>Germany · Web Design Agency</i>"]
    independent["Independent Work"]
    dietz["Dietz Webdesign<br/><i>Predecessor · Original agency</i>"]

    john --> leadupfront
    leadupfront --> rawlens
    rawlens --> operations["Operations Platform<br/><i>Private business system</i>"]
    rawlens --> portal["Customer Portal<br/><i>Private booking system</i>"]

    john --> kruershof
    kruershof --> pala["PALA Consulting Group"]
    kruershof --> realty["Pala Realty"]
    kruershof --> smaragd["Smaragdblüte"]
    kruershof --> artwussow["ARTWussow"]
    kruershof --> autocenter["Autocenter Mülheim Göksu"]
    kruershof --> schweriner["Schweriner Goldankauf"]
    kruershof --> dachdecker["Dachdecker Wittler"]
    kruershof --> renate["Renate Reimann Energiemedizin"]
    kruershof --> nptrucks["NP Trucks"]
    kruershof --> goldantik["Das Gold und Antikhaus"]

    john --> independent
    independent --> flashy["FlashyVendor<br/><i>USA · Luxury Jewelry</i>"]
    independent --> steven["Steven Noora<br/><i>Philippines · Filmography Portfolio</i>"]

    john --> dietz
    dietz -.-> kruershof

    classDef root fill:#f5f5f5,stroke:#111111,color:#111111,stroke-width:2px
    classDef branch fill:#bdbdbd,stroke:#111111,color:#111111,stroke-width:2px
    classDef project fill:#171717,stroke:#8b8b8b,color:#f5f5f5
    class john root
    class kruershof,leadupfront,independent,rawlens branch
    class dietz,autocenter,dachdecker,smaragd,schweriner,nptrucks,renate,artwussow,pala,goldantik,realty,steven,flashy,operations,portal project
    linkStyle default stroke:#8b8b8b
```

## Systems

**[Krüershof Workflow System]** — A 36-node production workflow governing client intake, routing, quality control, and delivery.

**[The Elite Triad]** — A multi-model orchestration layer built around specialized roles, generator-verifier separation, bounded escalation, and adaptive routing.

<table>
  <thead>
    <tr>
      <th align="center"></th>
      <th align="center">GitHub Streak</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">
        <table>
          <tr>
            <td align="center"><img src="https://user-images.githubusercontent.com/74038190/212907120-c72ded50-c4ef-4d96-8a23-e4b69757a907.jpg" alt="Developer illustration one" width="120" /></td>
            <td align="center"><img src="https://user-images.githubusercontent.com/74038190/216318921-21620ac8-e31f-42b0-b7dd-80ee2f424c2f.png" alt="Developer illustration two" width="120" /></td>
          </tr>
          <tr>
            <td align="center"><img src="https://user-images.githubusercontent.com/74038190/215768933-8904f263-b421-4fd1-a5b0-83c1f07df757.png" alt="Developer illustration three" width="120" /></td>
            <td align="center"><img src="https://user-images.githubusercontent.com/74038190/214373791-293fa4f8-9ebd-4de5-9cb5-56033dc3d6ce.jpg" alt="Developer illustration four" width="120" /></td>
          </tr>
        </table>
      </td>
      <td align="center"><img src="https://camo.githubusercontent.com/8778ac1f5cb4456a2cd55438fd4f62d5b6d7c3dc2ab44549b1a9b50c08a40386/68747470733a2f2f6769746875622d726561646d652d73747265616b2d73746174732e6865726f6b756170702e636f6d2f3f757365723d6d696b65617363656e6478267468656d653d746f6b796f6e6967687426686964655f626f726465723d74727565" alt="GitHub Streak" width="500" /></td>
    </tr>
  </tbody>
</table>

<p align="center">
  <img
    src="https://gitlyy.vercel.app/api/contribution?username=mikeascendx&amp;hide_border=true"
    alt="GitHub contribution graph"
    width="100%"
  />
</p>

<p align="center">
  <a href="https://ko-fi.com/mikeascendx"><img src="https://storage.ko-fi.com/cdn/kofi3.png?v=6" alt="Buy me a coffee at ko-fi.com" height="42"></a>
</p>

<p align="center">
  <img
    src="https://komarev.com/ghpvc/?username=mikeascendx&amp;color=555555&amp;style=flat-square&amp;label=Profile+Views"
    alt="Profile Views"
  />
</p>

[Krüershof Workflow System]: https://dietz-workflow-system.pages.dev
[The Elite Triad]: https://the-elite-triad.pages.dev
