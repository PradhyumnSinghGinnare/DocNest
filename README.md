# DocNest

<h1 align="center">Google-Docs Like Clone With Flutter Web and Appwrite</h1>

<p align="center">  
This project is a demo application showing how to create a rich text editing experience, similar to Google Docs, using <a href="https://flutter.dev/">Flutter</a>, <a href="https://appwrite.io/?utm_source=influencer&utm_medium=homepage&utm_campaign=funwithflutter">Appwrite</a>, and <a href="https://pub.dev/packages/flutter_quill">Flutter-Quill</a>.
</br>

### Realtime Changes - Collaboration
Collaborate with other users on the same document in real-time.

<p align="center">
<img alt="Realtime changes demos" src="https://user-images.githubusercontent.com/13705472/162619976-6896a508-10b0-444f-84ac-894ada48e18a.gif" />
</p>

### Create and Open Documents
Easily create and re-open documents. Everything is saved to your Appwrite database.

<p align="center">
<img alt="Create a new document demo" src="https://user-images.githubusercontent.com/13705472/162619991-f6742a46-e1ec-46d8-8701-6922398248ca.gif" />
</p>

### Authentication - Sign-in and Create New Accounts
Easy authentication using Appwrite.

<p align="center">
<img alt="Registration demo" src="https://user-images.githubusercontent.com/13705472/162620014-ee411a9f-9f1c-419a-b846-5bbb876701bd.gif" />
</p>


## Packages
Packages used in this project.

<img alt="built with appwrite logo"  src="https://user-images.githubusercontent.com/13705472/162620390-34dbbcab-b9c2-44b9-966e-adf6d7a63933.svg" align="right" width="32%"/>

### Backend: Appwrite
[Appwrite](https://appwrite.io/?utm_source=influencer&utm_medium=homepage&utm_campaign=funwithflutter) is an open-source alternative to Firebase and makes it possible to easily integrate authentication and add a backend database for your application. Appwrite also makes it possible to add real-time listeners to your database quickly.

- [Appwrite Docs](https://appwrite.io/docs?utm_source=influencer&utm_medium=docs&utm_campaign=funwithflutter)
- [Appwrite Github](https://github.com/appwrite/?utm_source=influencer&utm_medium=github&utm_campaign=funwithflutter)
- [Appwrite Discord](https://discord.com/invite/GSeTUeA?utm_source=influencer&utm_medium=discord&utm_campaign=funwithflutter)


### Rich Text Editor: Flutter-Quill
[FlutterQuill](https://pub.dev/packages/flutter_quill) is a rich text editor and a [Quill](https://quilljs.com/docs/formats) component for [Flutter](https://github.com/flutter/flutter). This package makes it easy to sync incremental changes to other editors (real-time changes).

**Honorable Mentions**: [SuperEditor](https://superlist.com/SuperEditor/)

### State Management: Riverpod
[Riverpod](https://riverpod.dev/) is an excellent choice for a state management solution in your Flutter application, and this tutorial demonstrates multiple scenarios where Riverpod truly shines. If you've not used it before, this project may change your mind. The video tutorial highlights numerous excellent features and demos how to structure and organize your providers.

### Routing: Routemaster
[Routemaster](https://pub.dev/packages/routemaster) simplifies the complexity of Flutter's 2.0 Navigator. This project creates two separate route maps:
- Authenticated routes
- Not authenticated routes

Riverpod, and the authentication state from Appwrite, determine which routes to allow.

### Other Packages
[Equatable](https://pub.dev/packages/equatable): A Dart package that helps implement value-based equality without needing to explicitly override `==` and `hashCode`.
- [UUID](https://pub.dev/packages/uuid): Simple, fast generation of [RFC4122](https://www.ietf.org/rfc/rfc4122.txt) UUIDs.
- [Logging](https://pub.dev/packages/logging): Provides APIs for debugging and error logging.
