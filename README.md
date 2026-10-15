# Cloud Computing - Opdracht 1

## Beschrijving

Deze repository bevat de applicatie voor de eerste opdracht van Cloud Computing. De applicatie en de bijbehorende database worden met Docker Compose opgestart.


## 1. Repository clonen

Open een terminal in de map waarin je het project wilt bewaren en gebruik.


```powershell
git clone https://github.com/Sander0070/cloud-computing.git
```

Ga vervolgens naar de projectmap:

```powershell
cd cloud-computing
```

## 2. Omgevingsvariabelen configureren

Maak een `.env`-bestand aan op basis van het meegeleverde `.env.example`-bestand.

**Belangrijk:** Vul idere element van het `.env`-bestand aan eigen gegevens.

## 3. Applicatie en database starten

Controleer of je je in de hoofdmap van het project bevindt. In deze map moet het bestand `compose.yaml` staan.

Start vervolgens de applicatie en de database met:

```powershell
docker compose up --build -d
```

## 4. Applicatie openen

Open een browser en navigeer naar:

**http://localhost:8000/**

