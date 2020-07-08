# WPFWeatherApp-master
Siguiendo el curso Windows Presentation Foundation Masterclass (en Udemy-LP Academy-Eduardo Rosas *****, muy recomendable) conseguimos esta aplicación para consultar el tiempo (meteo) actual en una ciudad. Excelente ejemplo de arquitectura MVVM

Por un lado utilizamos la API de Accuweather para la obtención de los datos de las condiciones actuales de la meteo de una determinada localización (Clase AccuWeatherHelper en la carpeta ViewModel\Helpers)
Por otro aprendemos los componentes básicos de MVVM: 
* INotifyPropertyChanged interface : se utiliza en la clase WeatherVM: ViewModel\WeatherVM.cs 
* Using Design Mode Bindings
* The ICommand interface: se utiliza en la clase SeacrhCommand: ViewModel\Commands\SearchCommand.cs 
* The ObservableCollection<T> class. Se implementa en la Propiedad Cities de la clase WeatherVM: ViewModel\WeatherVM.cs y se enlaza en la vista:-->View\WeatherWindow.xaml--> ... <ListView ItemsSource="{Binding Cities} ...
  
Por último también vemos como utilizar IValueConverter interface lo que permite mejorar la experiencia del usuario
