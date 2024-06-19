# Violence Detection for Edge AI

Metodi e risultati per ottimizzare modelli di Deep-Learning per l'Edge-AI a partire dai modelli: "*MobileNet-V3 Small + ConvLSTm*" E "*MobileNet-V3 Small + BiLSTM*".

## Disclaimer


A causa dei limiti di spazio imposti da GitHub, il dataset e i modelli sono presenti nella seguente cartella <a href="https://drive.google.com/drive/folders/1vwOICAaE-ESojIxODMB_rZ9fEC2hxBwT?usp=sharing">GDrive</a>.

## Description

La repository è suddivisa nelle seguenti cartelle: 

* **Modelli standard**: Contiene i codici per fare inferenza sui modelli: "*MobileNet-V3 Small + ConvLSTm*" E "*MobileNet-V3 Small + BiLSTM*".
* **Addestramento modelli**: Contiene il codice per addestrare i due modelli di partenza, ovvero: "*MobileNet-V3 Small + ConvLSTm*" E "*MobileNet-V3 Small + BiLSTM*".
* **Quantizzazione**: Contiene i codici per effettuare e valutare tutte le più famose tecniche di quantizzazione(Int, Int fallback e Float16).
* **Clusterizzazione**: Contiene i codici per effettuare e valutare alcune tipologie di clustering.
* **Pruning**: Contiene i codici per effettuare e valutare alcune tipologie di pruning.
*  **Tecnica Mista**: Contiene codice per implementazioni miste di tecniche di ottimizzazione, ad esempio: "Pruning al 50% + Quantizzazione Post training".
* **Future Implementazioni**: Contiene codici che molto probabilmente saranno implementati in un prossimo futuro.
* **Cestino**: Codici scartati e/o non ottimali per lo scopo della repository.


## Autori e Contributi

<table>
  <tr>
    <td><a href="https://github.com/lucabellantee"><strong>Luca Bellante</strong></a></td>
    <td><progress value="50" max="100"></progress> 50%</td>
  </tr>
  <tr>
    <td><a href="https://github.com/AgneseBruglia"><strong>Agnese Bruglia</strong></a></td>
    <td><progress value="50" max="100"></progress> 50%</td>
  </tr>
</table>


## Version History

* 0.1
    * Initial Release


