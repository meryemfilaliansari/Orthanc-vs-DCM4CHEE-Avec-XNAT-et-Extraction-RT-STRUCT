# Plateforme PACS Multi-Systemes

Plateforme professionnelle de comparaison et analyse entre DCM4CHEE et Orthanc PACS avec integration XNAT et extraction RT-STRUCT.

## A Propos

Cette plateforme integre trois systemes PACS majeurs (DCM4CHEE, Orthanc, XNAT) pour offrir une solution complete de gestion d'images medicales DICOM.

### Fonctionnalites Cles

- **Comparaison Performance**: Analyse detaillee des temps de reponse
- **Anonymisation RGPD/HIPAA**: Deidentification conforme via XNAT
- **Workflow RT-STRUCT**: Pipeline automatise d'extraction et visualisation 3D
- **Visualisation Avancee**: OHIF Viewer avec mesures et annotations
- **Monitoring Temps Reel**: Grafana et Prometheus pour metriques

## Demarrage Rapide

### Installation

```bash
git clone https://github.com/meryemfilaliansari/Orthanc-vs-DCM4CHEE-Avec-XNAT-et-Extraction-RT-STRUCT.git
cd Orthanc-vs-DCM4CHEE-Avec-XNAT-et-Extraction-RT-STRUCT
docker compose up -d
```

### Acces aux Interfaces

| Interface | URL |
|-----------|-----|
| Dashboard | http://localhost:3000 |
| API Docs | http://localhost:8000/docs |
| DCM4CHEE | http://localhost:8080/dcm4chee-arc/ui2 |
| Orthanc | http://localhost:8042 |
| OHIF Viewer | http://localhost:5173 |
| Grafana | http://localhost:3001 |

## Documentation Complete

Consultez la documentation detaillee pour plus d'informations:

- [Installation](quickstart/installation.md)
- [Configuration](quickstart/configuration.md)
- [Premier Demarrage](quickstart/first-run.md)
- [Architecture](architecture/overview.md)
- [Microservices](architecture/microservices.md)
- [Tableau de Bord](guides/dashboard.md)
- [Troubleshooting](troubleshooting/common-issues.md)
