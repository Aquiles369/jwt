<h1 align="center">𓆩⚜𓆪 JWT 𓆩⚜𓆪</h1>	


<br>


<p align="center">
 <img  height="470rem" alt="GIF" src="https://github.com/Aquiles369/iconos/blob/main/loquillo.gif">
</p>

##

<picture>
  <img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNm5uNHl6eW5sMXB6Y25obnRpeG52Mm12dmtkNTk2dGFyYjVyejl0bCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/B6zEPouWkkekb8exj3/giphy.gif" width="75px">
</picture> ༒︎ JWT ༒︎

<br>

<p>
𓆩⚜𓆪 JWT 𓆩⚜𓆪 es un formato de token utilizado comúnmente para autenticación, autorización y manejo de sesiones en aplicaciones web y APIs, compuesto por header, payload y firma, siendo una superficie muy importante en bug bounty para buscar fallos como validación incorrecta de firmas, aceptación de algoritmos inseguros, confusión de algoritmos, manipulación de claims, expiración mal validada, reutilización de tokens, exposición de información sensible, problemas con <code>kid</code>, <code>jku</code> o <code>jwk</code>, claves débiles y bypasses de autenticación o autorización.
</p>

<p>
✦ Es la colección de informes más completa que pude lograr, buscando en diferentes rincones de Internet.
</p>

<p>
<strong>✦ Tip:</strong> en caso de que FreeMedium esté caído, casi siempre aparece algún mirror o alternativa similar.
</p>

<p>
✦ Las técnicas y patrones generales de cada informe me los reservo, al menos hasta el momento de publicar mi tool web, anteriormente llamada <strong>Excalibur</strong> y hoy en día llamada <strong>❦ Lanza del Cielo Invertida ❦</strong>.
</p>

<p>
𓆩⚜𓆪 Saludos 𓆩⚜𓆪
</p>

<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

<picture>
  <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExNHg3dThzazNwN2lrYjVscGdwMmRyN2xlb2NrcWJsamUwMXFjbXM5YSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/1CoTS8bsIdPaRNS7fs/giphy.gif" width="80px">
</picture>
<b>༒︎ JWT ༒︎</b>
<br><br>

**✦ En esta sección encontrarás 32 informes reales sobre JWT que leí, estudié y guardé en mi gestor de informes para bug bounty personal.**
<br><br>


## ꧁ Lista de informes link directo ꧂
```yam
https://medium.com/@vishalsharma445500/hacking-apis-series-14-36-mastering-jwt-json-web-tokens-7d12477f6dd8
https://medium.com/@vishalsharma445500/hacking-apis-series-15-36-jwt-json-web-token-attacks-20c5dc6fbe3f
https://medium.com/@mohaba746/dont-trust-the-token-the-art-of-jwt-attacks-1a76aae95a63
https://medium.com/@vipulparveenjain/exploiting-flawed-jwt-signature-verification-jwt-series-part-2a-eea18c52f36c
https://medium.com/@WorldVLive/stop-making-these-5-fatal-jwt-mistakes-and-how-to-fix-them-ad9d07046998
https://medium.com/@musab_alharany/10-ways-to-exploit-json-web-token-jwt-ac5f4efbc41b
https://medium.com/@AlQa3Qa3_M0X0101/how-i-was-able-to-get-account-takeover-via-idor-form-jwt-caaf7ea58aa
https://medium.com/@nirdesh123raya/exploiting-json-web-tokens-jwt-for-full-account-takeover-13ed5e4ab3bd
https://medium.com/@ydvashish/how-i-gained-unauthorized-access-to-organization-admin-panel-by-jwt-manipulation-67a6ff09bfa1
https://freedium-mirror.cfd/https://cybersecuritywriteups.com/5-jwt-logic-confusion-bypassing-authentication-b247f7910f70
https://freedium-mirror.cfd/https://hcibo.medium.com/our-nemesis-anonymous-jwt-token-48b1a7c90a77
https://dk9510.medium.com/json-web-tokens-vulnerabilities-and-exploitation-9c6689616396
https://freedium-mirror.cfd/https://medium.com/cloud-security/oauth-and-jwt-attacks-3840fe2a113f
https://infosecwriteups.com/stealing-jwt-tokens-via-oauth-redirect-uri-manipulation-a-critical-vulnerability-abbd579b5443
https://medium.com/@roshan.reju/attacking-json-web-tokens-892fc76b7fcf
https://dannynweke.medium.com/jwt-security-common-vulnerabilities-and-how-to-test-them-8d7badc38a01
https://infosecwriteups.com/revisiting-jwt-token-forgery-attack-on-a-recent-bounty-target-bfe4a423f3df
http://freedium-mirror.cfd/https://karol-mazurek.medium.com/appsec-tales-viii-jwt-7e28b8fc0dd2
https://medium.com/@ProwlSec/jwt-auth-gone-wild-the-unexpected-twist-a0b2ed943225
https://freedium-mirror.cfd/https://infosecwriteups.com/unbelievable-security-hole-jwt-secret-in-a-series-b-funded-company-540434b54e59
https://medium.com/@ksreemosmar/exploiting-weak-jwt-secrets-in-a-bug-bounty-target-377f79b57b26
https://freedium-mirror.cfd/https://medium.com/@reyanshicodes/your-jwt-implementation-will-get-you-hacked-the-vulnerabilities-83ff27919600
https://medium.com/@monethic/jwt-post-exploitation-vectors-cbaa90ac1a65
https://medium.com/@shoaibbinrashid11/jwt-hacking-handbook-from-ctfs-to-real-world-pentesting-eb8850a4e833
https://medium.com/@h4x0r_dz/23000-for-authentication-bypass-file-upload-arbitrary-file-overwrite-2578b730a5f8
https://freedium-mirror.cfd/https://codewithvamp.medium.com/how-a-forged-jwt-token-exposed-egift-cards-of-all-users-worth-millions-685f6cd20824
https://medium.com/@samhilliard/in-this-post-ill-show-you-how-to-use-jwt-tool-to-analyze-and-exploit-jwt-vulnerabilities-in-97c62a0e6ac5
https://freedium-mirror.cfd/https://infosecwriteups.com/jwt-security-in-2025-are-we-finally-free-from-leaks-3552fce24690
https://medium.com/@cyberspecter/from-frustration-to-discovery-how-a-simple-tip-helped-me-uncover-a-jwt-data-exposure-d149a7afe4a2
https://medium.com/@d7meealz/jwt-authentication-bypass-eebed5346079
https://freedium-mirror.cfd/https://medium.verylazytech.com/jwt-hacking-toolkit-20-real-hacker-techniques-to-master-authentication-attacks-acc75a736e6e
https://medium.com/@mayank_prajapati/jwt-attacks-algorithm-confusion-vulnerability-ce4bcfa3854a

```

<br>


<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

<picture>
  <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExb3podm1rZ3Y4amU5d3hpdmxucGhydGd3MnF1ZndudzhlenV0eWxkMiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/cByts7baForf4uj0eU/giphy.gif" width="80px">
</picture>
<b>“Analizar cientos de técnicas no te da más payloads, te da otra forma de observar aplicaciones.”</b>
<picture>
  <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExb3podm1rZ3Y4amU5d3hpdmxucGhydGd3MnF1ZndudzhlenV0eWxkMiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/cByts7baForf4uj0eU/giphy.gif" width="80px">
</picture>
<br><picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
