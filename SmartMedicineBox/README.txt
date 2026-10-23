RUN ON WINDOWS 11
1. Extract ZIP.
2. Open extracted SmartMedicineBox_AllFeatures folder.
3. In File Explorer address bar type cmd and press Enter.
4. Run: dotnet restore
5. Run: dotnet run --urls http://localhost:5080
6. Open http://localhost:5080. Keep terminal open; Ctrl+C stops server.

FEATURES: schedule management, manual taken/not-taken recording with timestamps, history, family-view demo alerts, editable sample environment readings, four simulated servo buttons, and a rule-based adherence summary.

LIMITATIONS: in-memory data clears on restart; no database, authentication, real SMS/email, live ESP32 integration, physical servo control, or deep-learning model. Manual status does not prove medicine was swallowed. This is a student demo, not a medical device.
