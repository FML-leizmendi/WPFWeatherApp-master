# WPFWeatherApp-master
Siguiendo el curso Windows Presentation Foundation Masterclass (en Udemy-LP Academy-Eduardo Rosas, muy recomendable) conseguimos esta aplicación para consultar el tiempo (meteo) actual en una ciudad. Excelente ejemplo de arquitectura MVVM

Por un lado utilizamos la API de Accuweather para la obtención de los datos de las condiciones actuales de la meteo de una determinada localización (Clase AccuWeatherHelper en la carpeta ViewModel\Helpers)
Por otro aprendemos los componentes básicos de MVVM: 
* INotifyPropertyChanged interface
* Using Design Mode Bindings
* The ICommand interface
* The ObservableCollection<T> class
  
Por último también vemos como utilizar IValueConverter interface lo que permite mejorar la experiencia del usuario
