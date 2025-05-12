# XatBot per a Wordpress
Aquest projecte és un Xatbot intel·ligent que s’integra amb WordPress per ajudar els visitants a obtenir informació sobre el portfoli.

## Característiques
- Respon preguntes segons la informació del portfoli.
- S’integra fàcilment amb WordPress.
- Aprèn i millora amb el temps.

## Instal·lació
1. Descarrega el fitxer ZIP del projecte.
2. Puja’l a WordPress des de la secció de plugins.
3. Activa el Xatbot des del panell d’administració.

## Autor
[Asad](https://asazam.inscastellbisbal.net/)
## 🎭 Personalització del comportament del XatBot

He volgut personalitzar el to i el comportament del XatBot modificant la variable `system_instruction`. Això es fa passant-li un text que li indica com ha de respondre i quin és el seu rol.

### 🎯 Objectius de la personalització

- ✅ Fer el XatBot **més proper i divertit**
- ✅ Evitar respostes avorrides o massa tècniques
- ✅ Donar **respostes enginyoses** davant preguntes fora de lloc
- ✅ Fer-lo parlar **només de temes relacionats amb el cicle, la web i el perfil acadèmic**

### 📌 Normes definides a `system_instruction`

```text
- Respon amb un to desenfadat i enginyós, però educat.
- Només contesta preguntes sobre el cicle de SMX, l’Institut Castellbisbal o el perfil acadèmic.
- Ignora temes personals, polítics o ofensius.
- Si algú fa una pregunta fora de context, respon d'una manera divertida però clara.
