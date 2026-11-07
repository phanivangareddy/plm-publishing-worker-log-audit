# PLM Publishing Worker Log Audit

**by Phani Vanga**

This free Windows app reads publishing logs from Windchill visualization workers. It shows how many documents were published, which ones failed, why they failed, and where the time went.

It runs only on your own Windows PC. It needs no internet connection, sends nothing anywhere and uses no AI service.

## What's new in 1.1

- **Documents by day:** see how many documents were published or failed each day. Click a day to list every document with its number, name, type, worker and time, then download the list for Excel.
- **Choose dates and workers:** look at one date range, one worker or any set of workers, such as Office worker 1 or Creo worker 2.
- **Live updates:** the app can re-read the logs every 30 seconds to 15 minutes while workers are still writing to them.

This repository holds the installer and the user guide only, with no source code.

## Download

**[Download PLM-Publishing-Worker-Log-Audit-1.1-Windows.zip](https://github.com/phanivangareddy/plm-publishing-worker-log-audit/releases/latest/download/PLM-Publishing-Worker-Log-Audit-1.1-Windows.zip)** (about 10 MB), or see [all releases](../../releases).

## Get started

1. Download **PLM-Publishing-Worker-Log-Audit-1.1-Windows.zip**.
2. Right-click it and choose **Properties**. If you see **Unblock**, tick it.
3. Extract it to a local folder, such as `C:\PLM-Log-Audit`.
4. Double-click **PLM-Publishing-Worker-Log-Audit.exe**, and keep the black window open while you use it.
5. In your browser, click **Add folder**, choose your log folder, then click **Analyse logs**.
6. Use **Show results for** to pick dates and workers, and **Documents by day** to see what was published each day.

Windows may warn that the app is from an unknown publisher. Choose **More info**, then **Run anyway**, if your company allows it.

For full instructions, read the [user guide (PDF)](PLM-Publishing-Worker-Log-Audit-User-Guide.pdf).

## Requests, problems and comments

Open an [Issue](../../issues) to report a problem, request a change or leave a comment. Please don't attach logs or reports that contain confidential document names.

## Licence

PLM Publishing Worker Log Audit is free to use, and you may share the unchanged installer. You may not modify, decompile or resell it. See [LICENSE.txt](LICENSE.txt).

It is not made by, or connected with, PTC.

---

Support and feedback: **phani.vanga@outlook.com**
