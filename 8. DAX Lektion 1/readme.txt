För att kunna ladda om data till Emmas fruits and cookies måste ni ändra URL i source-steget i Power Query för alla tabeller så att de går till excelfilen
som ni har laddat ner på er dator.

Denna rad --v
Excel.Workbook(File.Contents("C:\Users\DATH7646\OneDrive - Nexer AB\_Uppdrag\EC utbildning\Power BI vt 2024\git\ssbi\6. DAX Lektion 1\Emmas Fruits and Cookies.xlsx")