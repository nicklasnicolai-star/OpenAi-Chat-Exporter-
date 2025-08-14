
# 🗂️ OpenAI Chat Sorter / Exporter

## Was macht dieses Tool?

Dieses Python-Skript exportiert automatisch alle Chatverläufe aus einer 'conversations.json' (dem offiziellen OpenAI-Export) in einzelne '.docx'-Dateien. Jeder Chat wird als eigenes Word-Dokument gespeichert – mit dem Titel als Dateinamen, sauber getrennt nach „User“ und „ChatGPT“. Die Chats sind damit unabhängig von OpenAI, leicht archivierbar, und jederzeit durchsuchbar.

**Features:**

* Vollautomatischer Export: Alle Chats werden in einem Rutsch verarbeitet.
* Saubere Formatierung: Jede Nachricht ist klar getrennt, Nutzer und KI werden hervorgehoben.
* Titel = Dateiname: Übersichtlichkeit garantiert, kein Datenchaos.
* Entfernt unsaubere Steuerzeichen für maximale Kompatibilität.

------------------------------------------------------------------------------------------------------

## Warum gibt es das?

OpenAI macht es seinen Nutzern leider nicht gerade leicht, ihre eigenen Daten ordentlich zu sichern. Dieses Tool schafft Abhilfe und gibt dir volle Kontrolle über deine Konversationen – egal, ob du archivieren, durchsuchen oder einfach unabhängig bleiben willst.

------------------------------------------------------------------------------------------------------

## Voraussetzungen

*  Python 3.7+
* 'python-docx'
   Installieren mit:

  'pip install python-docx'
  

------------------------------------------------------------------------------------------------------

## Anwendung

1. Lade deinen OpenAI-Chat-Export als 'conversations.json' herunter.
2. Lege diese Datei ins gleiche Verzeichnis wie das Skript.
3. Starte das Skript:

   'python openai_sorter.py'
   
4. Die fertigen '.docx'-Dateien findest du im Ordner 'chats_output'.

------------------------------------------------------------------------------------------------------

## Hinweis

Dieses Tool ist bewusst **einfach gehalten** und tut genau das, was es soll – nicht mehr und nicht weniger. Wer mehr will, kann es jederzeit anpassen oder erweitern.

------------------------------------------------------------------------------------------------------

# 🗂️ OpenAI Chat Sorter / Exporter (English)

## What does this tool do?

This Python script exports automatically all chat conversations from a 'conversations.json' file (the official OpenAI export) into individual '.docx' files. Each chat becomes its own Word document, named with chat title for name of the document, with all turns clearly marked as "User" or "ChatGPT". This makes your chats independent of OpenAI, easy to archive, and fully searchable.

**Features:**

* Fully automated export: All chats processed in one go.
* Clean formatting: Every message is separated, roles are highlighted.
* Title = file name: Maximum clarity, no data mess.
* Removes non-standard control characters for best compatibility.

------------------------------------------------------------------------------------------------------

## Why does this exist?

OpenAI unfortunately doesn’t make it easy to keep your own data organized. This tool gives you full control over your conversations – archive, search, or just be independent from OpenAI’s platform.

------------------------------------------------------------------------------------------------------

## Requirements

*  Python 3.7+
* 'python-docx'
   Install with:
  
  'pip install python-docx'


------------------------------------------------------------------------------------------------------

## Usage

1. Download your OpenAI chat export as 'conversations.json'.
2. Place it in the same directory as the script.
3. Run the script:

   'python openai_sorter.py'
   
4. Your '.docx' files will appear in the 'chats_output' folder.

------------------------------------------------------------------------------------------------------

## Note

This tool is **kept simple by design** – it does exactly what it claims, nothing more, nothing less. Anyone who needs more can easily adapt or extend it.

------------------------------------------------------------------------------------------------------
