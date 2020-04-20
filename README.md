# TEM_project
L’articolo che ha ispirato il presente lavoro è uno studio di Volker Morath et al. il cui obiettivo era,
partendo da un dataset di immagini di alcuni tipi cellulari, stimare l’area del nucleo e del citoplasma tramite tecniche di preprocessing
e formule di stereologia. In questo progetto si è partiti dal medesimo dataset che contiene le immagini microscopiche di alcune cellule e 
le rispettive segmentazioni in nucleo, citoplasma e background. L’obiettivo è dunque costruire un algoritmo in grado di segmentare le
immagini fornite in input, sfruttando un tipo di rete neurale convoluzionale molto utilizzato nell’ambito della segmentazione di immagini
biomedicali: la  U-network. 

L’obiettivo del lavoro era sviluppare una Unet in grado di effettuare una segmentazione delle immagini date in input, per farlo ho 
utilizzato il dataset Segmentation Dataset for Transmission Electron Microscopic Cell Recordings e ho comparato due reti neurali aventi 
come algoritmo di ottimizzazione rispettivamente Adam e SGD. Il modello con Adam optimizer è risultato essere più performante in termini 
di riduzione della funzione perdita e quindi dell’errore raggiungendo il 95% di accuratezza (validazione del test set).
