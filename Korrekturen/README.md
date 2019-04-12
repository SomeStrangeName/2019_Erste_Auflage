## Korrekturen

Trotz sorgfältigem Redigieren und Prüfung lassen sich Fehler nie ganz vermeiden. Daher bietet wir Ihnen in diesem Dokument 
Korrekturen.
<br>
An dieser Stelle möchten wie Sie als Leser/Leserin unseres Buches dazu ermutigen, uns gefundene Fehler zu melden, so dass wir diese in besagtes Dokument aufnehmen und in eventuellen nächsten Auflagen berücksichtigen 
können. Vielen Dank dafür!

#### Seite 143 

Im Listing 5.1 : 
```python 
init = tf.global_variables_initializer()
``` 

#### Seite 147 

Aktualisierter Text: *<i>ersetzen Sie die tf.Variable() a, b, c und d durch tf.placeholder():</i>*  

#### Seite 157 

Anpassung des Parameters *noise* in: 

```python 
noise = np.random.randint(low=-5, high=5, size=input.shape)
``` 

Folgende Zeilen vertauschen:
```python 
import matplotlib.pyplot as plt
matplotlib.use('TkAgg')` 
``` 

#### Seite 212

Aktualisierter Code: `rain_predict`→`train_predict`

#### Seite 370

Aktualisierter Code:

```python 
eval_metric_ops = {"accuracy": eval_accuracy } 
print(eval_accuracy)
```

#### Seite 376

Folgende Zeilen löschen: 
```python 
num_epochs = None
``` 
```python 

num_epochs = 2
``` 
