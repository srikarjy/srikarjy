<svg width="1180" height="610" viewBox="0 0 1180 610" xmlns="http://www.w3.org/2000/svg">
<defs>
<clipPath id="cardClip"><rect x="0" y="0" width="1180" height="610" rx="24" ry="24"/></clipPath>
<linearGradient id="accentGrad" x1="0%" y1="0%" x2="100%" y2="0%">
<stop offset="0%" stop-color="#7C3AED"/>
<stop offset="50%" stop-color="#22D3EE"/>
<stop offset="100%" stop-color="#10B981"/>
<animateTransform attributeName="gradientTransform" type="translate" values="-0.3 0;0.3 0;-0.3 0" dur="8s" repeatCount="indefinite"/>
</linearGradient>
<linearGradient id="asciiGrad" x1="0%" y1="0%" x2="0%" y2="100%">
<stop offset="0%" stop-color="#22D3EE"/>
<stop offset="100%" stop-color="#7C3AED"/>
<animateTransform attributeName="gradientTransform" type="translate" values="0 -0.4;0 0.4;0 -0.4" dur="6s" repeatCount="indefinite"/>
</linearGradient>
<linearGradient id="shimmerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
<stop offset="0%" stop-color="#22D3EE" stop-opacity="0"/>
<stop offset="50%" stop-color="#22D3EE" stop-opacity="0.9"/>
<stop offset="100%" stop-color="#7C3AED" stop-opacity="0"/>
<animateTransform attributeName="gradientTransform" type="translate" values="-1.2 0;1.2 0;-1.2 0" dur="4s" repeatCount="indefinite"/>
</linearGradient>
<radialGradient id="blob0" cx="50%" cy="50%" r="50%">
<stop offset="0%" stop-color="#2563EB" stop-opacity="0.35"/>
<stop offset="100%" stop-color="#2563EB" stop-opacity="0"/>
</radialGradient>
<radialGradient id="blob1" cx="50%" cy="50%" r="50%">
<stop offset="0%" stop-color="#7C3AED" stop-opacity="0.35"/>
<stop offset="100%" stop-color="#7C3AED" stop-opacity="0"/>
</radialGradient>
<radialGradient id="blob2" cx="50%" cy="50%" r="50%">
<stop offset="0%" stop-color="#10B981" stop-opacity="0.35"/>
<stop offset="100%" stop-color="#10B981" stop-opacity="0"/>
</radialGradient>
<filter id="glow" x="-60%" y="-60%" width="220%" height="220%">
<feGaussianBlur stdDeviation="4.5" result="blur"/>
<feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
</filter>
<filter id="softGlow" x="-100%" y="-100%" width="300%" height="300%">
<feGaussianBlur stdDeviation="10"/>
</filter>
<filter id="noise"><feTurbulence type="fractalNoise" baseFrequency="0.85" numOctaves="2" stitchTiles="stitch" result="noise"/><feColorMatrix in="noise" type="matrix" values="0 0 0 0 1  0 0 0 0 1  0 0 0 0 1  0 0 0 0.02 0"/></filter>
<clipPath id="leftPanelClip"><rect x="0" y="0" width="448" height="610" rx="24" ry="24"/></clipPath>
<clipPath id="termClip"><rect x="0" y="0" width="660" height="538" rx="18" ry="18"/></clipPath>
</defs>
<g clip-path="url(#cardClip)">
<rect x="0" y="0" width="1180" height="610" fill="#030712"/>
<circle cx="160" cy="140" r="260" fill="url(#blob0)">
<animate attributeName="cx" values="120;200;120" dur="10s" repeatCount="indefinite"/>
<animate attributeName="cy" values="110;170;110" dur="12s" repeatCount="indefinite"/>
</circle>
<circle cx="708" cy="480" r="320" fill="url(#blob1)">
<animate attributeName="cx" values="668;748;668" dur="12s" repeatCount="indefinite"/>
<animate attributeName="cy" values="450;510;450" dur="14s" repeatCount="indefinite"/>
</circle>
<circle cx="900" cy="120" r="300" fill="url(#blob2)">
<animate attributeName="cx" values="860;940;860" dur="14s" repeatCount="indefinite"/>
<animate attributeName="cy" values="90;150;90" dur="16s" repeatCount="indefinite"/>
</circle>
<rect x="0" y="0" width="1180" height="610" filter="url(#noise)" opacity="0.5"/>
<g transform="translate(0,0)">
<g clip-path="url(#leftPanelClip)">
<rect x="0" y="0" width="448" height="610" fill="#0F172A" fill-opacity="0.55"/>
<g font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="13.5" fill="url(#asciiGrad)" filter="url(#glow)">
<animateTransform attributeName="transform" type="translate" values="0 0;0 -8;0 0" dur="5s" repeatCount="indefinite" additive="sum"/>
<text x="34" y="60.0" opacity="0" xml:space="preserve">        .:-=+*#%%#*+=-:.        <animate attributeName="opacity" from="0" to="1" begin="0.0s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="84.5" opacity="0" xml:space="preserve">     :=*%@@@@@@@@@@@@@@%*=:     <animate attributeName="opacity" from="0" to="1" begin="0.35s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="109.0" opacity="0" xml:space="preserve">   -*%@@@@#=:......:=#@@@@%*-   <animate attributeName="opacity" from="0" to="1" begin="0.7s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="133.5" opacity="0" xml:space="preserve">  =%@@@@+.   .:=+*+=:.  +@@@@%= <animate attributeName="opacity" from="0" to="1" begin="1.0499999999999998s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="158.0" opacity="0" xml:space="preserve"> +@@@@#:  :+%@@@@@@@@%+:  :#@@@@+<animate attributeName="opacity" from="0" to="1" begin="1.4s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="182.5" opacity="0" xml:space="preserve">.@@@@%. .*@@@@@@@@@@@@@@*. .%@@@@.<animate attributeName="opacity" from="0" to="1" begin="1.75s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="207.0" opacity="0" xml:space="preserve">%@@@@:  #@@@@@%*++*%@@@@#  :@@@@%<animate attributeName="opacity" from="0" to="1" begin="2.0999999999999996s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="231.5" opacity="0" xml:space="preserve">@@@@%  =@@@@#:      :#@@@@=  %@@@@<animate attributeName="opacity" from="0" to="1" begin="2.4499999999999997s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="256.0" opacity="0" xml:space="preserve">@@@@#  %@@@#   .::.   #@@@%  #@@@@<animate attributeName="opacity" from="0" to="1" begin="2.8s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="280.5" opacity="0" xml:space="preserve">@@@@#  %@@@#  :%@@%:  #@@@%  #@@@@<animate attributeName="opacity" from="0" to="1" begin="3.15s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="305.0" opacity="0" xml:space="preserve">@@@@%  =@@@@=       .=@@@@=  %@@@@<animate attributeName="opacity" from="0" to="1" begin="3.5s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="329.5" opacity="0" xml:space="preserve">.@@@@:  #@@@@%*=:.:=*%@@@@#  :@@@@.<animate attributeName="opacity" from="0" to="1" begin="3.8499999999999996s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="354.0" opacity="0" xml:space="preserve"> +@@@@#:  -+#%@@@@@@%#+-  :#@@@@+ <animate attributeName="opacity" from="0" to="1" begin="4.199999999999999s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="378.5" opacity="0" xml:space="preserve">  =%@@@@+:.    ..    .:+%@@@@%=  <animate attributeName="opacity" from="0" to="1" begin="4.55s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="403.0" opacity="0" xml:space="preserve">   -*%@@@@@#+==+=+#@@@@@%*-    <animate attributeName="opacity" from="0" to="1" begin="4.8999999999999995s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="427.5" opacity="0" xml:space="preserve">     :=*%@@@@@@@@@@@@%*=:       <animate attributeName="opacity" from="0" to="1" begin="5.25s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="452.0" opacity="0" xml:space="preserve">        .:-=+*##*+=-:.          <animate attributeName="opacity" from="0" to="1" begin="5.6s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="476.5" opacity="0" xml:space="preserve">                                 <animate attributeName="opacity" from="0" to="1" begin="5.949999999999999s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="501.0" opacity="0" xml:space="preserve">   &gt; srikar@github ~ whoami     <animate attributeName="opacity" from="0" to="1" begin="6.3s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="525.5" opacity="0" xml:space="preserve">   &gt; building at the biology-ml <animate attributeName="opacity" from="0" to="1" begin="6.6499999999999995s" dur="0.4s" fill="freeze"/></text>
<text x="34" y="550.0" opacity="0" xml:space="preserve">     boundary_                  <animate attributeName="opacity" from="0" to="1" begin="7.0s" dur="0.4s" fill="freeze"/></text>
</g>
<rect x="0" y="0" width="448" height="3" fill="#22D3EE" opacity="0.25">
<animate attributeName="y" values="0;610;0" dur="7s" repeatCount="indefinite"/>
</rect>
<rect x="446.5" y="0" width="1.5" height="610" fill="url(#shimmerGrad)" opacity="0.7"/>
</g>
</g>
<g transform="translate(484,36)">
<g clip-path="url(#termClip)">
<rect x="0" y="0" width="660" height="538" rx="18" ry="18" fill="#0F172A" fill-opacity="0.55"/>
<rect x="0" y="0" width="660" height="188.29999999999998" fill="white" opacity="0.04"/>
<rect x="0" y="0" width="660" height="38" fill="#FFFFFF" fill-opacity="0.04"/>
<circle cx="20" cy="19" r="5.5" fill="#EF4444"/>
<circle cx="38" cy="19" r="5.5" fill="#F59E0B"/>
<circle cx="56" cy="19" r="5.5" fill="#10B981"/>
<text x="330.0" y="24" text-anchor="middle" font-family="ui-monospace, monospace" font-size="12" fill="#94A3B8">srikar@github: ~/profile</text>
<text x="26" y="74" font-family="ui-monospace, monospace" font-size="20" fill="#F8FAFC" opacity="0">Hi 👋, I'm Srikar Yadhunandan<animate attributeName="opacity" from="0" to="1" begin="0.2s" dur="0.5s" fill="freeze"/></text>
<g font-family="ui-monospace, monospace" font-size="17" fill="url(#accentGrad)">
<text x="26" y="114">AI/ML Engineer<animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.0;0.0;0.2208;0.2208;1" dur="12.0s" repeatCount="indefinite"/></text>
<text x="26" y="114">Backend Engineer<animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.25;0.25;0.4708;0.4708;1" dur="12.0s" repeatCount="indefinite"/></text>
<text x="26" y="114">Data Scientist Fellow @ ChiEAC<animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.5;0.5;0.7208;0.7208;1" dur="12.0s" repeatCount="indefinite"/></text>
<text x="26" y="114">Biotech x Machine Learning<animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.75;0.75;0.9708;0.9708;1" dur="12.0s" repeatCount="indefinite"/></text>
</g>
<rect x="276" y="100" width="9" height="17" fill="#22D3EE"><animate attributeName="opacity" values="1;1;0;0" dur="1s" repeatCount="indefinite"/></rect>
<line x1="26" y1="156" x2="634" y2="156" stroke="#FFFFFF" stroke-opacity="0.12"/>
<g font-family="ui-monospace, monospace" font-size="14.5" fill="#94A3B8">
<text x="26" y="182" opacity="0">📍  Chicago, IL<animate attributeName="opacity" from="0" to="1" begin="1.4s" dur="0.4s" fill="freeze"/></text>
<text x="26" y="209" opacity="0">🎓  MS CS, Boston University<animate attributeName="opacity" from="0" to="1" begin="1.75s" dur="0.4s" fill="freeze"/></text>
<text x="26" y="236" opacity="0">🔬  Current Focus: BioFeed AI<animate attributeName="opacity" from="0" to="1" begin="2.0999999999999996s" dur="0.4s" fill="freeze"/></text>
<text x="26" y="263" opacity="0">🌐  github.com/srikarjy<animate attributeName="opacity" from="0" to="1" begin="2.4499999999999997s" dur="0.4s" fill="freeze"/></text>
</g>
<line x1="26" y1="304" x2="634" y2="304" stroke="#FFFFFF" stroke-opacity="0.12"/>
<text x="26" y="328" font-family="ui-monospace, monospace" font-size="12.5" fill="#94A3B8" opacity="0">SKILLS<animate attributeName="opacity" from="0" to="1" begin="3s" dur="0.4s" fill="freeze"/></text>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="3.2s" dur="0.35s" fill="freeze"/>
<rect x="26" y="344" width="69.8" height="26" rx="13" ry="13" fill="#111827" fill-opacity="0.6" stroke="url(#accentGrad)" stroke-width="1" filter="url(#glow)">
<animate attributeName="stroke-opacity" values="0.5;1;0.5" dur="3.0s" repeatCount="indefinite"/>
</rect>
<text x="60.9" y="361.5" text-anchor="middle" font-family="ui-monospace, monospace" font-size="12.5" fill="#F8FAFC">Python</text>
</g>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="3.3200000000000003s" dur="0.35s" fill="freeze"/>
<rect x="105.8" y="344" width="77.1" height="26" rx="13" ry="13" fill="#111827" fill-opacity="0.6" stroke="url(#accentGrad)" stroke-width="1" filter="url(#glow)">
<animate attributeName="stroke-opacity" values="0.5;1;0.5" dur="3.4s" repeatCount="indefinite"/>
</rect>
<text x="144.35" y="361.5" text-anchor="middle" font-family="ui-monospace, monospace" font-size="12.5" fill="#F8FAFC">PyTorch</text>
</g>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="3.4400000000000004s" dur="0.35s" fill="freeze"/>
<rect x="192.89999999999998" y="344" width="77.1" height="26" rx="13" ry="13" fill="#111827" fill-opacity="0.6" stroke="url(#accentGrad)" stroke-width="1" filter="url(#glow)">
<animate attributeName="stroke-opacity" values="0.5;1;0.5" dur="3.8s" repeatCount="indefinite"/>
</rect>
<text x="231.45" y="361.5" text-anchor="middle" font-family="ui-monospace, monospace" font-size="12.5" fill="#F8FAFC">FastAPI</text>
</g>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="3.56s" dur="0.35s" fill="freeze"/>
<rect x="280.0" y="344" width="99.0" height="26" rx="13" ry="13" fill="#111827" fill-opacity="0.6" stroke="url(#accentGrad)" stroke-width="1" filter="url(#glow)">
<animate attributeName="stroke-opacity" values="0.5;1;0.5" dur="4.2s" repeatCount="indefinite"/>
</rect>
<text x="329.5" y="361.5" text-anchor="middle" font-family="ui-monospace, monospace" font-size="12.5" fill="#F8FAFC">PostgreSQL</text>
</g>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="3.68s" dur="0.35s" fill="freeze"/>
<rect x="389.0" y="344" width="69.8" height="26" rx="13" ry="13" fill="#111827" fill-opacity="0.6" stroke="url(#accentGrad)" stroke-width="1" filter="url(#glow)">
<animate attributeName="stroke-opacity" values="0.5;1;0.5" dur="3.0s" repeatCount="indefinite"/>
</rect>
<text x="423.9" y="361.5" text-anchor="middle" font-family="ui-monospace, monospace" font-size="12.5" fill="#F8FAFC">Docker</text>
</g>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="3.8000000000000003s" dur="0.35s" fill="freeze"/>
<rect x="468.8" y="344" width="47.9" height="26" rx="13" ry="13" fill="#111827" fill-opacity="0.6" stroke="url(#accentGrad)" stroke-width="1" filter="url(#glow)">
<animate attributeName="stroke-opacity" values="0.5;1;0.5" dur="3.4s" repeatCount="indefinite"/>
</rect>
<text x="492.75" y="361.5" text-anchor="middle" font-family="ui-monospace, monospace" font-size="12.5" fill="#F8FAFC">AWS</text>
</g>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="3.92s" dur="0.35s" fill="freeze"/>
<rect x="526.7" y="344" width="62.5" height="26" rx="13" ry="13" fill="#111827" fill-opacity="0.6" stroke="url(#accentGrad)" stroke-width="1" filter="url(#glow)">
<animate attributeName="stroke-opacity" values="0.5;1;0.5" dur="3.8s" repeatCount="indefinite"/>
</rect>
<text x="557.95" y="361.5" text-anchor="middle" font-family="ui-monospace, monospace" font-size="12.5" fill="#F8FAFC">Neo4j</text>
</g>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="4.04s" dur="0.35s" fill="freeze"/>
<rect x="26" y="378" width="62.5" height="26" rx="13" ry="13" fill="#111827" fill-opacity="0.6" stroke="url(#accentGrad)" stroke-width="1" filter="url(#glow)">
<animate attributeName="stroke-opacity" values="0.5;1;0.5" dur="4.2s" repeatCount="indefinite"/>
</rect>
<text x="57.25" y="395.5" text-anchor="middle" font-family="ui-monospace, monospace" font-size="12.5" fill="#F8FAFC">React</text>
</g>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="4.16s" dur="0.35s" fill="freeze"/>
<rect x="98.5" y="378" width="62.5" height="26" rx="13" ry="13" fill="#111827" fill-opacity="0.6" stroke="url(#accentGrad)" stroke-width="1" filter="url(#glow)">
<animate attributeName="stroke-opacity" values="0.5;1;0.5" dur="3.0s" repeatCount="indefinite"/>
</rect>
<text x="129.75" y="395.5" text-anchor="middle" font-family="ui-monospace, monospace" font-size="12.5" fill="#F8FAFC">Swift</text>
</g>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="4.28s" dur="0.35s" fill="freeze"/>
<rect x="171.0" y="378" width="40.6" height="26" rx="13" ry="13" fill="#111827" fill-opacity="0.6" stroke="url(#accentGrad)" stroke-width="1" filter="url(#glow)">
<animate attributeName="stroke-opacity" values="0.5;1;0.5" dur="3.4s" repeatCount="indefinite"/>
</rect>
<text x="191.3" y="395.5" text-anchor="middle" font-family="ui-monospace, monospace" font-size="12.5" fill="#F8FAFC">Go</text>
</g>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="4.4s" dur="0.35s" fill="freeze"/>
<rect x="221.6" y="378" width="91.7" height="26" rx="13" ry="13" fill="#111827" fill-opacity="0.6" stroke="url(#accentGrad)" stroke-width="1" filter="url(#glow)">
<animate attributeName="stroke-opacity" values="0.5;1;0.5" dur="3.8s" repeatCount="indefinite"/>
</rect>
<text x="267.45" y="395.5" text-anchor="middle" font-family="ui-monospace, monospace" font-size="12.5" fill="#F8FAFC">LangGraph</text>
</g>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="4.52s" dur="0.35s" fill="freeze"/>
<rect x="323.3" y="378" width="62.5" height="26" rx="13" ry="13" fill="#111827" fill-opacity="0.6" stroke="url(#accentGrad)" stroke-width="1" filter="url(#glow)">
<animate attributeName="stroke-opacity" values="0.5;1;0.5" dur="4.2s" repeatCount="indefinite"/>
</rect>
<text x="354.55" y="395.5" text-anchor="middle" font-family="ui-monospace, monospace" font-size="12.5" fill="#F8FAFC">Kafka</text>
</g>
<line x1="26" y1="474" x2="634" y2="474" stroke="#FFFFFF" stroke-opacity="0.12"/>
<circle cx="26" cy="498" r="11" fill="none" stroke="url(#accentGrad)" stroke-width="1.4" filter="url(#glow)">
<animate attributeName="r" values="11;12.5;11" dur="3s" begin="0.0s" repeatCount="indefinite"/>
</circle>
<text x="26" y="502" text-anchor="middle" font-family="ui-monospace, monospace" font-size="10" fill="#F8FAFC">G</text>
<text x="44" y="502" font-family="ui-monospace, monospace" font-size="12" fill="#94A3B8">github.com/srikarjy</text>
<circle cx="226" cy="498" r="11" fill="none" stroke="url(#accentGrad)" stroke-width="1.4" filter="url(#glow)">
<animate attributeName="r" values="11;12.5;11" dur="3s" begin="0.4s" repeatCount="indefinite"/>
</circle>
<text x="226" y="502" text-anchor="middle" font-family="ui-monospace, monospace" font-size="10" fill="#F8FAFC">L</text>
<text x="244" y="502" font-family="ui-monospace, monospace" font-size="12" fill="#94A3B8">linkedin.com/in/srikar-yadhunandan-142309162</text>
</g>
</g>
<rect x="1" y="1" width="1178" height="608" rx="24" ry="24" fill="none" stroke="#FFFFFF" stroke-opacity="0.08" stroke-width="1.5"/>
<rect x="1" y="1" width="1178" height="608" rx="24" ry="24" fill="none" stroke="url(#shimmerGrad)" stroke-width="1.5"/>
</g>
</svg>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Srikar_Yadhunandan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/srikar-yadhunandan-142309162)
[![Location](https://img.shields.io/badge/Chicago,_IL-ChiEAC-10B981?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

</div>

## About

I am a Data Scientist Fellow (AI/ML & Backend Engineering) at ChiEAC in Chicago, working across ML pipelines, iOS development, and backend platform engineering. My background bridges biotechnology and computer science: a B.Tech in Biotechnology from Manipal Institute of Technology, followed by an MS in Computer Science from Boston University.

I build the kind of systems that sit at the boundary of biology and machine learning: RAG pipelines over scientific literature, agentic reasoning systems that refuse unsupported claims, forecasting models on clinical time series, and the backend infrastructure to ship all of it. My work is published in IEEE FNWF 2024 (`arXiv:2504.18029`).

**Currently building:** BioFeed AI, a native iOS biotech intelligence app I am building end to end, SwiftUI front end, FastAPI/Python backend, semantic search across an 8,500+ article corpus, and a personalized recommendation engine.

## Projects

<table>
<tr>
<td width="50%" valign="top">

### 🧬 [FlowCast](https://github.com/srikarjy/FlowCast)
A Go CLI that parses Nextflow trace and MultiQC output from nf-core/rnaseq runs and narrates QC failures with honest, confidence-tagged reasoning instead of guessing at causes.

- Modified Z-score (MAD) classifier: **F1 0.870** vs. 0.706 fixed-threshold baseline (+23.2%)
- Claude API narrator tags every claim Observed / Reported / Unknown, cutting unsupported causal claims **76.3%** on a 48-case golden set
- Deterministic replay via a Go + Python event log backed by SQLite

`Go` `Python` `SQLite` `OpenTelemetry`

</td>
<td width="50%" valign="top">

### 🩸 [GlucoPulse](https://github.com/srikarjy/GlucoPulse)
A glucose forecasting pipeline built on 306K+ real CPGM readings from 25 Type 1 diabetes patients, from raw ingestion through a Temporal Fusion Transformer served in production.

- 30 min horizon: **RMSE ‑25.0%**, Zone A **+8.8pp** (91.2%) vs. persistence baseline
- 60 min horizon: **RMSE ‑21.0%**, Zone A **+10.4pp** (78.6%)
- Kafka ingestion, TimescaleDB hypertables, PySpark feature engineering, Airflow, ONNX/INT8 inference

`Kafka` `PyTorch` `TimescaleDB` `Airflow` `ONNX`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 [Aletheia](https://github.com/srikarjy/Aletheia)
A multi-agent debate system (advocate, skeptic, empiricist, synthesizer) that calibrates its own confidence against memory of past debates, and knows when it doesn't have enough evidence to trust that memory.

- Expected Calibration Error reduced **0.184 → 0.117** using 47 prior debate results
- Detects **13/16** known memory-induced regressions via automated counterfactual evaluation
- LangGraph StateGraph orchestration with thread-scoped and cross-thread memory stores

`Python` `LangGraph` `PostgreSQL` `Claude API`

</td>
<td width="50%" valign="top">

### 🔬 [PharmGraph](https://github.com/srikarjy/PharmGraph)
A full-stack pharmacogenomics graph explorer that reconciles messy, duplicated clinical annotation data into a clean, provenance-tracked knowledge graph.

- Disambiguated **28** protein IDs, collapsed **343** duplicate CYP2C9 rows
- Two-layer provenance cross-referencing PharmGKB and PubMed
- CPIC evidence tiering with **31** passing tests

`Python` `Neo4j` `React`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛰️ [Biolab MCP Server](https://github.com/srikarjy/biolab-mcp-server)
A production-grade, multi-tenant MCP server exposing biolab data sources (ClinVar, ChEMBL, PubMed) over a proper backend, JWT auth, SSE streaming, and rate limiting included.

`Go` `JWT` `SSE`

</td>
<td width="50%" valign="top">

### 📱 BioFeed AI *(in progress)*
A native SwiftUI iOS app that aggregates biotech literature and news across 200+ tickers, deduplicates semantically over an 8,500+ article corpus, and learns what to surface from real click and dwell-time signals.

- Recommendation system improves offline replay CTR **+30%** over a popularity baseline
- Anomaly detection pipeline surfaced 3 candidate early-signal events in a 2-month historical backtest

`SwiftUI` `FastAPI` `PostgreSQL` `Docker`

</td>
</tr>
</table>

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=srikarjy&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Srikar's GitHub stats" width="49%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=srikarjy&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" width="30%" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=srikarjy&theme=tokyonight&hide_border=true" alt="GitHub streak" width="60%" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=srikarjy&theme=tokyo-night&hide_border=true&area=true" alt="Contribution activity graph" width="80%" />

</div>

## Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/srikar-yadhunandan-142309162)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/srikarjy)

</div>
