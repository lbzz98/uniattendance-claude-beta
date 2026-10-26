# UniAttendance Claude Beta

Independent experimental development channel for UniAttendance, a native university timetable, attendance, syllabus, exams and materials app for UniCamillus Medicine and Surgery in English, Rome.

This public repository contains **compiled macOS packages and their dedicated update feed only**. It is separate from the main UniAttendance Beta channel. Source code, personal data, license files and private signing keys are not published here. The Claude variant has its own app identity, data directory, credential/session storage and update channel. Installing it does not migrate data from the main app.

## Installazione macOS

1. Apri [Releases](https://github.com/lbzz98/uniattendance-claude-beta/releases) e seleziona la release Claude desiderata. Essendo un canale beta, non usare il solo collegamento `/releases/latest`.
2. Scarica lo ZIP **UniAttendance-Claude-…-macOS-universal.zip** dagli Assets (Intel e Apple Silicon; macOS14 o successivo).
3. Apri lo ZIP. Per provarla puoi aprire **UniAttendance Claude Beta.app** dalla cartella estratta oppure trascinarla in Applicazioni mantenendo questo nome distinto. Non sostituire UniAttendance.app o UniAttendance Beta.app.
4. La build è firmata ad hoc e non notarizzata. Se macOS la blocca, tenta una prima apertura, quindi usa **Impostazioni di Sistema → Privacy e sicurezza → Apri comunque**, esclusivamente per questa copia scaricata da questo repository e riconosciuta dal proprietario della beta. Non disattivare globalmente le protezioni del Mac.
5. L'app richiede una licenza specifica: copia la richiesta di attivazione, inviala privatamente al gestore della beta e importa il file ricevuto. Non pubblicare richieste o licenze nelle issue. Il periodo rimanente è visibile nell'app.
6. Scegli anno e gruppo quando richiesto. L'archivio della variante è separato; le slide e le presenze dell'altra app non vengono importate automaticamente.
7. Per Materiali Online e Badgiate accedi al portale ufficiale nell'app e completa personalmente il CAPTCHA. Evita accessi simultanei alla WebApp da più varianti se il portale invalida le sessioni.
8. Gli aggiornamenti successivi si controllano e installano dall'app, tramite il feed esclusivo di questo repository.

## macOS installation

1. Open [Releases](https://github.com/lbzz98/uniattendance-claude-beta/releases) and choose the Claude release; this beta channel does not rely on `/releases/latest`.
2. Download **UniAttendance-Claude-…-macOS-universal.zip** from Assets (Intel and Apple Silicon; macOS14+).
3. Extract the ZIP and open **UniAttendance Claude Beta.app**, or move it to Applications keeping its distinct name. Do not replace the main UniAttendance or UniAttendance Beta app.
4. This ad-hoc-signed build is not notarized. If blocked, attempt opening once and use **System Settings → Privacy & Security → Open Anyway** only for this recognized copy from this repository. Do not disable Mac security globally.
5. Copy this app's activation request and privately request a dedicated license from the beta owner. Import the returned file. Do not post licenses or requests in public issues. Remaining license time is displayed in the app.
6. Choose your study year and group. Data is separate from the main app and is not automatically migrated.
7. For online Materials and Badge scans, sign in to the official embedded portal and complete the CAPTCHA yourself. Avoid simultaneous portal sessions across variants if the university invalidates them.
8. Future updates are checked and installed in the app using this repository's dedicated feed.

## Update channel

[macOS Claude update manifest](https://raw.githubusercontent.com/lbzz98/uniattendance-claude-beta/main/updates/macos-beta.json). Platform key: `macos-claude`. Packages from the main distribution are not interchangeable.

No Windows package is included. iPhone/iPad development uses a separate local Xcode project; the macOS ZIP cannot be installed on iOS. This project is an independent student tool, not an official UniCamillus product.
