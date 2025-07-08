# 🌟 Gids voor Interactieve Immersie Lessen

## 🎯 Perfect voor Immersieve Taallessen!

Dit AI-platform biedt alles wat je nodig hebt voor boeiende, interactieve taallessen met volledige immersie.

## 🚀 Snelle Setup (5 minuten)

### 1. ✅ API Key Verkrijgen (GRATIS)
- Ga naar: [makersuite.google.com/app/apikey](https://makersuite.google.com/app/apikey)
- Login en klik "Create API Key"
- Kopieer je key en plak in `.env.local`

### 2. ✅ Project Starten
```bash
npm run dev
```
Open dan: http://localhost:3000

## 🎓 Immersieve Les Scenario's

### 🗣️ **Scenario 1: Conversatie Training**
**Doel**: Natuurlijke gesprekken in doeltaal
**Werkwijze**:
1. Student gebruikt 🎙️ **spraakherkenning** om te praten
2. AI reageert in de doeltaal met natuurlijke stem
3. Automatische **transcriptie** voor feedback
4. **30 verschillende stemmen** voor authentieke ervaring

**Voorbeeld prompt voor de AI**:
```
"Je bent een vriendelijke cafe eigenaar in Parijs. Voer een gesprek met een toerist die iets wil bestellen. Reageer alleen in het Frans, met eenvoudige zinnen."
```

### 📸 **Scenario 2: Visuele Context Lessen**
**Doel**: Vocabulaire leren met echte situaties
**Werkwijze**:
1. Gebruik 📸 **camera** om foto te maken van objecten/situaties
2. Upload meerdere afbeeldingen tegelijk
3. AI beschrijft in doeltaal wat ze ziet
4. Interactieve woordenschat oefeningen

**Voorbeeld**:
- Foto van restaurant menu → AI verklaart gerechten in doeltaal
- Foto van straat → AI beschrijft wat er gebeurt
- Foto van kledingwinkel → AI helpt met kleuren/maten

### 🎵 **Scenario 3: Authentieke Materialen**
**Doel**: Echte content uit de doelcultuur
**Werkwijze**:
1. Upload **audio/video** van native speakers
2. AI transcribeert automatisch
3. Creëert oefeningen en uitleg
4. Student luistert en reageert

**Voorbeelden**:
- Nederlandse radio fragmenten
- Franse nieuwsberichten  
- Spaanse liedjes
- Duitse podcasts

### 📄 **Scenario 4: Document Analyse**
**Doel**: Complexe teksten begrijpen
**Werkwijze**:
1. Upload **PDF's/documenten** in doeltaal
2. AI legt moeilijke passages uit
3. Maakt samenvattingen en vragen
4. Helpt met grammatica en structuur

## 🛠️ Praktische Tips voor Docenten

### 🎭 **Rollenspel Scenarios**
```
Prompts voor verschillende situaties:
- "Je bent een reisagent in Berlijn..."
- "Je werkt in een boekwinkel in Madrid..."
- "Je bent kok in een Italiaans restaurant..."
```

### 🔊 **TTS Instellingen Optimaliseren**
- **Microsoft TTS**: Snelle, duidelijke uitspraak (standaard)
- **Gemini AI TTS**: 30 stemmen + emoties voor variatie
- **Emotie keuzes**: Enthousiast voor motivatie, Kalm voor uitleg
- **Snelheid**: Start langzaam (0.75x), verhoog geleidelijk

### 📊 **Voortgang Bijhouden**
- **Word export**: AI responses opslaan voor evaluatie
- **Copy functie**: Goede voorbeelden verzamelen
- **Transcriptie historie**: Uitspraak verbetering volgen

## 🌍 Taalspecifieke Instellingen

### 🇳🇱 **Nederlands als Tweede Taal**
```
System prompt:
"Spreek langzaam en duidelijk Nederlands. Gebruik eenvoudige zinnen en leg moeilijke woorden uit. Wees geduldig en bemoedigend."
```

### 🇬🇧 **Engels Conversatie**
```
System prompt:
"You're a friendly English tutor. Speak clearly, use simple vocabulary, and encourage the student. Always respond in English only."
```

### 🇫🇷 **Frans Immersie**
```
System prompt:
"Tu es un professeur de français patient. Parle lentement et clairement. Utilise des phrases simples et explique les mots difficiles."
```

### 🇩🇪 **Duits Leren**
```
System prompt:
"Du bist ein geduldiger Deutschlehrer. Sprich langsam und deutlich. Verwende einfache Sätze und erkläre schwierige Wörter."
```

## 🎮 Interactieve Oefeningen

### **Woorden Raden Spel**
1. Upload foto van object
2. AI geeft hints in doeltaal
3. Student raadt het woord
4. Feedback via TTS

### **Verhaal Opbouwen**
1. Student begint een zin
2. AI vervolgt het verhaal
3. Samen een verhaal maken
4. Focus op grammatica en vocabulaire

### **Situatie Simulaties**
1. AI beschrijft een scenario
2. Student reageert via spraak
3. Natuurlijke conversatie ontwikkelt zich
4. Real-time feedback en correcties

## 🔧 Technische Tips

### **Optimale Audio Kwaliteit**
- Gebruik headset voor spraakherkenning
- Stille ruimte voor beste transcriptie
- Test verschillende TTS stemmen per taal

### **Bestandsformaten**
- **Audio**: MP3, WAV (beste kwaliteit)
- **Afbeeldingen**: JPG, PNG (< 20MB)
- **Documenten**: PDF, DOCX (< 10MB)

### **Performance**
- Chrome/Edge browser aanbevolen
- Goede internetverbinding voor real-time features
- Gebruik Gemini 2.5 Flash voor snelste responses

## 🎯 Evaluatie & Assessment

### **Automatische Evaluatie**
```
Prompt voor AI:
"Evalueer de uitspraak en grammatica van deze student. Geef constructieve feedback in het Nederlands en highlight 3 verbeterpunten."
```

### **Voortgang Portfolio**
- Word export van beste gesprekken
- Audio opnames van voortgang
- Foto documentatie van visuele oefeningen

## 🌟 Geavanceerde Features

### **Multi-Modal Lessen**
Combineer verschillende media types:
- Foto + Audio + Tekst document
- Video frame + conversatie
- Grafiek + uitleg + discussie

### **Realtime Internet Toegang**
Gebruik Gemini 2.0 Flash voor:
- Actuele nieuws in doeltaal
- Cultuur informatie opzoeken
- Real-time vertaling verificatie

## 🚀 Les Scenario Template

```markdown
### Les: [ONDERWERP] - Niveau: [A1/A2/B1/B2/C1/C2]

**Doel**: [Specifieke leerdoelen]

**Materialen**: 
- [ ] Audio bestand
- [ ] Foto's/afbeeldingen  
- [ ] Tekst document
- [ ] Camera voor real-time

**AI Prompt**:
"[Specifieke rol en instructies voor AI]"

**Activiteiten**:
1. [Warming-up activiteit]
2. [Hoofdactiviteit]
3. [Afsluiting/evaluatie]

**Verwachte Output**:
- [ ] Transcriptie van gesprek
- [ ] Word document met feedback
- [ ] Audio opname van verbeteringen
```

---

## 🎉 **Succes gegarandeerd!**

Met deze geavanceerde AI-tool maak je de meest boeiende en effectieve immersie lessen die je studenten ooit hebben gehad! 

**💡 Pro tip**: Start met eenvoudige scenario's en bouw langzaam de complexiteit op. De AI past zich aan het niveau van je studenten aan.

---
*Voor vragen of extra ondersteuning, check de volledige documentatie in README.md*