# Starter app GNU/Linux avec GTK

Projet de démarrage d'application desktop Dart/Flutter visant les distributions GNU/Linux, utilisant [le paquet GTK fourni par Canonical](https://pub.dev/packages/gtk) (Gnome *look & feel* avec [le thème Yaru](https://github.com/ubuntu/yaru), le thème par défaut de la distribution Ubuntu)

> Le pack est basé sur [l'exemple fourni par le paquet officiel gtk2.*](https://pub.dev/packages/gtk/example)

## Getting Started

~~~bash
flutter pub get
flutter run
~~~

### Interaction avec la ligne de commande (optionnel)

> The GtkApplication widget allows listening to remote application instances' command-line arguments and file open requests from within the widget tree.

[Suivre les instructions](https://pub.dev/packages/gtk) données dans la section *Getting Started* pour modifier l'*embedder* Linux `linux/my_application.cc`.

## Références

- [gtk 2.1.0](https://pub.dev/packages/gtk), la librairie Dart fournie par Canonical
- [Libadwaita ❤️ Flutter](https://github.com/gtk-flutter/libadwaita), Libadwaita's widgets for Flutter. Following Gnome HIG and available on all platforms.
- [adwaita 1.1.0 ](https://pub.dev/packages/adwaita), adwaita theme (color scheme)
- [The official Flutter Yaru Theme and Widgets Suite](https://github.com/ubuntu/yaru.dart), yaru theme, alternative a adwaita
- [Using GtkApplication](https://developer.gnome.org/documentation/tutorials/application.html)