cat << 'EOF' > README.md
<div align="center">

<img src="./assets/apple-hero.svg" width="100%" alt="Turan Akpınar - 2Run - Neuron" />

<br/><br/>

<a href="https://github.com/tuakpina">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=15&duration=3500&pause=1500&color=86868B&center=true&vCenter=true&width=680&lines=Designing+fault-tolerant+SaaS+infrastructures+and+distributed+systems.;High-throughput+asynchronous+backends+powered+by+FastAPI+%26+Redis.;Laying+the+architectural+foundations+of+Neuron." alt="Typing SVG" />
</a>

</div>

<br/>

---

### `01` &nbsp; Core Architecture & Tech Specs

<table>
  <tr>
    <td width="33%" valign="top">
      <br/>
      <p align="center">
        <img src="https://skillicons.dev/icons?i=python,fastapi&theme=dark" height="42" />
      </p>
      <h4 align="center">Application & Runtime</h4>
      <p align="center">
        <sub><b>Python & FastAPI</b><br/>Asenkron I/O, yüksek eşzamanlı (high-concurrency) mikroservis mimarileri, tip güvenli REST/WebSocket API tasarımı.</sub>
      </p>
      <br/>
    </td>
    <td width="33%" valign="top">
      <br/>
      <p align="center">
        <img src="https://skillicons.dev/icons?i=redis,postgres,mysql&theme=dark" height="42" />
      </p>
      <h4 align="center">Data & In-Memory Layer</h4>
      <p align="center">
        <sub><b>Redis & SQL</b><br/>Dağıtık önbellekleme (distributed caching), Pub/Sub mesaj kuyrukları, rate-limiting ve ilişkisel veritabanı optimizasyonu.</sub>
      </p>
      <br/>
    </td>
    <td width="33%" valign="top">
      <br/>
      <p align="center">
        <img src="https://skillicons.dev/icons?i=docker,linux,nginx&theme=dark" height="42" />
      </p>
      <h4 align="center">Infrastructure & Delivery</h4>
      <p align="center">
        <sub><b>Docker & Cloud Native</b><br/>İzole konteyner orkestrasyonu, sıfır kesintili (zero-downtime) SaaS dağıtımları ve yatay ölçeklenebilir sunucu altyapısı.</sub>
      </p>
      <br/>
    </td>
  </tr>
</table>

<br/>

### `02` &nbsp; Vision — **Neuron**

> **Neuron**, ölçeklenebilir SaaS ürünleri ve yüksek performanslı bulut altyapıları geliştirmek üzere kurgulanan bağımsız bir yazılım girişimidir. Odak noktamız; karmaşık sistem yüklerini milisaniyelik tepki süreleriyle yöneten, yalın ve kendi kendini iyileştirebilen (self-healing) arka uç mimarileri inşa etmektir.

<br/>

### `03` &nbsp; System Telemetry

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=tuakpina&show_icons=true&bg_color=00000000&title_color=F5F5F7&text_color=86868B&icon_color=2997FF&hide_border=true&count_private=true" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=tuakpina&show_icons=true&bg_color=00000000&title_color=1D1D1F&text_color=86868B&icon_color=0066CC&hide_border=true&count_private=true" />
    <img height="155em" src="https://github-readme-stats.vercel.app/api?username=tuakpina&show_icons=true&bg_color=00000000&title_color=F5F5F7&text_color=86868B&icon_color=2997FF&hide_border=true&count_private=true" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=tuakpina&layout=compact&langs_count=5&bg_color=00000000&title_color=F5F5F7&text_color=86868B&hide_border=true" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=tuakpina&layout=compact&langs_count=5&bg_color=00000000&title_color=1D1D1F&text_color=86868B&hide_border=true" />
    <img height="155em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tuakpina&layout=compact&langs_count=5&bg_color=00000000&title_color=F5F5F7&text_color=86868B&hide_border=true" />
  </picture>
</div>

<br/>

<div align="center">
  <sub>
    <b>tuakpina</b> · alias <b>2Run</b> · Architecting <b>Neuron</b><br/>
    <span style="color: #86868b;">Istanbul, TR</span>
  </sub>
</div>
EOF
git add assets/apple-hero.svg README.md
git commit -m "Fix Apple SVG hero card and clean README"
git push