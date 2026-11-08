# Event Horizon — webversie op je eigen adres

In het artefact op claude.ai zijn microfoon en camera geblokkeerd; daar werkt alleen
de muziekbestand-modus. Zet je deze bestanden op een eigen https-adres, dan werkt alles:
microfoon, spraakherkenning (Silero) en hoofdvolging met de frontcamera.

## Op GitHub Pages zetten (gratis, ±5 minuten)

1. Ga naar github.com → **New repository**, naam bijvoorbeeld `event-horizon`, zet hem op **Public**
   (GitHub Pages is gratis voor publieke repositories).
2. Klik **Add file → Upload files** en upload `index.html` en `silero_vad.onnx`. Klik **Commit changes**.
3. Ga naar **Settings → Pages**. Kies bij *Source*: **Deploy from a branch**, branch **main**, map **/ (root)**, en klik **Save**.
4. Na ongeveer een minuut staat hij op `https://<jouw-gebruikersnaam>.github.io/event-horizon/`.

## Op de tablet

- Open het adres in **Chrome**, tik **Start met microfoon** en sta microfoon (en camera) toe.
- Tip: Chrome-menu → **Toevoegen aan startscherm**; dan start hij als app, schermvullend.
- De eerste keer laadt hij de spraakherkenning (~10 MB) en het gezichtsmodel van internet.
- Het tandwiel rechtsboven opent de instellingen (HUD, venster, kwaliteit, kalibreren, uitbraak-test).
- Wordt de tablet warm of hapert het beeld: kies in het menu **Kwaliteit** → licht.

## Goed om te weten

- De microfoon wordt geopend zónder automatische volumeregeling en ruisonderdrukking,
  zodat hij de kamer eerlijk hoort.
- Kalibratie wordt per apparaat in de browser bewaard.
- Wat de entiteit hoort en ziet, blijft op de tablet: er wordt geen geluid of beeld verstuurd.
