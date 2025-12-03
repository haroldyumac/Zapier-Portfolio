# Starred Email - Trello Task + Google Sheets Log 

**What it does**
When I star an email (in Gmail), Zapier will create a Trello task and log it into a new row on Google Sheets.

## Built in Zapier
1) Gmail - New Starred Email (trigger)
2) Trello - Create New Card (name = email subject, description = from/subject/link)
3) Google Sheets - Create Row (Timestamp, From, Subject, Message URL, CardURL, Status)

## Setup outside of Zapier
- Trello board/list: "Inbox Tasks"
- Google Sheet: "Starred Email Log"
- Columns = Timestamp, From, Subject, Threadlink, CardURL, Status

## How to verify
- Star any email in Gmail
- Confirm: Trrello card created, row added to Google Sheet

## Screenshots
-Zap: Overview <img width="904" height="542" alt="Starred Email Zap" src="https://github.com/user-attachments/assets/12e368dd-fb72-4c86-a2ac-9b2639e5ea3d" />
<p>&nbsp;</p>
-Trello: Before <img width="1279" height="707" alt="Trello Before" src="https://github.com/user-attachments/assets/9e807e62-5b46-448d-a2a1-cd7a903f021f" />
<p>&nbsp;</p>
-Trello: After <img width="1039" height="303" alt="Trello After" src="https://github.com/user-attachments/assets/cacd07eb-cbd8-4c6c-9b16-b558c1b04117" />
<p>&nbsp;</p>
-Google Sheet: Before <img width="1280" height="706" alt="Google Sheets Before" src="https://github.com/user-attachments/assets/1ddac95f-60f6-4183-8fbd-a16e672d039b" />
<p>&nbsp;</p>
-Google Sheet: After (double test) <img width="1278" height="335" alt="Google Sheets After (double test)" src="https://github.com/user-attachments/assets/988a8bbd-530e-42bb-822b-04f15d4099e3" />

