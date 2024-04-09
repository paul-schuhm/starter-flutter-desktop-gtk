# Starter app GNU/Linux avec GTK

Projet de démarrage d'application desktop Dart/Flutter visant les distributions GNU/Linux, utilisant [le paquet libadwaita](https://pub.dev/packages/libadwaita) et [le thème Adwaita](https://pub.dev/packages/adwaita), reproduisant [le GUI toolkit de la la librairie Adwaita](https://gnome.pages.gitlab.gnome.org/libadwaita/doc/1.5/index.html) ("Building blocks for modern GNOME applications"). Look and feel Gnome.

> Le pack est basé sur [l'exemple fourni par le paquet officiel adwaita 1.*](https://pub.dev/packages/adwaita/example)

## Getting Started

A la racine du dépôt :

~~~bash
cd starter_gnulinux_gtk
flutter pub get
flutter run
~~~

### Interaction avec la ligne de commande (optionnel)

> The GtkApplication widget allows listening to remote application instances' command-line arguments and file open requests from within the widget tree.

[Suivre les instructions](https://pub.dev/packages/gtk) données dans la section *Getting Started* pour modifier l'*embedder* Linux `linux/my_application.cc`.

## Thème

[Libadwaita](https://github.com/gtk-flutter/libadwaita) ne fournit que les Widgets. Pour le thème on peut choisir [Adwaita](https://pub.dev/packages/adwaita) ou [Yaru](https://pub.dev/packages/yaru). 

> Ici, le thème Adwaita est utilisé. 

## Références

### Paquets Dart

- [Libadwaita ❤️ Flutter](https://github.com/gtk-flutter/libadwaita), Libadwaita's widgets for Flutter. Following Gnome HIG and available on all platforms.
- [adwaita 1.1.0 ](https://pub.dev/packages/adwaita), thème Adwaita 
- [yaru 4.1.0](https://pub.dev/packages/yaru), thème Yaru
- [gtk 2.1.0](https://pub.dev/packages/gtk), GTK+ utilities for Flutter Linux applications, fournie par Canonical

### GUI Toolkit

- [The official Flutter Yaru Theme and Widgets Suite](https://github.com/ubuntu/yaru.dart), thème Yaru
- [Adwaita](https://gnome.pages.gitlab.gnome.org/libadwaita/doc/1.5/index.html), GUI Toolkit *Building blocks for modern GNOME applications*, surcouche GTK
- [Using GtkApplication](https://developer.gnome.org/documentation/tutorials/application.html), tutoriel sur l'usage de GTK