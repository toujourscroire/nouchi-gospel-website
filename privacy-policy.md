# Politique de confidentialité — Nouchi Gospel

**Dernière mise à jour : 15 octobre 2026**

Cette politique de confidentialité explique comment l'application **Nouchi Gospel** (« l'Application », « nous ») collecte, utilise, protège et transfère les informations des utilisateurs (« vous »).

En utilisant Nouchi Gospel, vous acceptez les pratiques décrites dans cette politique. Si vous n'êtes pas d'accord, nous vous invitons à ne pas utiliser l'Application.

---

## 1. Qui nous sommes

Nouchi Gospel est une application mobile **gratuite** proposant des versets bibliques traduits en Nouchi, des motivations quotidiennes, la Bible complète, un système de progression (streaks, récompenses) et des informations sur des événements et bons plans chrétiens.

- **Éditeur / Responsable du traitement** : Michel Kouakou
- **Pays d'établissement** : Côte d'Ivoire
- **Contact** : roschmichel12@gmail.com

---

## 2. Données que nous collectons

### 2.1 Données de compte (connexion optionnelle)

L'Application peut fonctionner sans compte. Si vous choisissez de vous connecter, nous recevons de votre fournisseur d'identité les informations suivantes :

**Via Google Sign-In :**
- Nom (tel qu'il apparaît sur votre compte Google)
- Adresse e-mail
- Photo de profil (si disponible)

**Via « Se connecter avec Apple » :**
- Nom (que vous pouvez choisir de masquer)
- Adresse e-mail — Apple peut fournir une **adresse relais privée** (`@privaterelay.appleid.com`) si vous choisissez de masquer votre e-mail réel

Dans les deux cas, l'authentification est gérée par **Firebase Authentication** (Google), qui nous attribue un **identifiant unique (UID)** pour votre compte. Nous ne voyons jamais votre mot de passe.

Ces informations servent uniquement à :
- Vous identifier dans l'Application
- Personnaliser votre expérience (prénom, avatar)
- Rattacher votre progression (voir 2.3) à votre compte

**Nous n'accédons jamais à vos contacts, e-mails, agenda, photos ou à tout autre contenu de votre compte Google ou Apple.**

### 2.2 Données de notification (push)

Pour vous envoyer le verset du jour, nous utilisons **Firebase Cloud Messaging (FCM)**. Cela génère un **token d'appareil** qui permet d'acheminer les notifications vers votre téléphone. Ce token est un identifiant **pseudonyme** : seul, il ne révèle pas votre identité, mais il est traité comme une donnée personnelle. Vous pouvez désactiver les notifications à tout moment depuis les réglages de votre téléphone.

### 2.3 Données de progression (stockées sur nos serveurs)

Si vous êtes connecté, les données liées à votre usage de l'Application sont enregistrées dans **Cloud Firestore** (Google Firebase), rattachées à votre UID :
- Votre **série de jours consécutifs** (streak)
- Vos **récompenses et points**
- Votre **historique de motivations** consultées

Ces données permettent de synchroniser votre progression entre vos appareils et de faire fonctionner le système de récompenses.

### 2.4 Données techniques et de sécurité

Comme la plupart des applications, nous collectons des données techniques minimales via **Firebase** :
- Type d'appareil et système d'exploitation (ex. iPhone 14, iOS 17)
- Version de l'Application et langue préférée
- Données d'intégrité de l'appareil via **Firebase App Check** (App Attest sur iOS), pour empêcher les usages frauduleux de l'Application

### 2.5 Données stockées uniquement sur votre appareil

Certaines préférences sont stockées **localement** sur votre appareil (via `SharedPreferences`) et **ne sont pas envoyées à nos serveurs** :
- Vos **versets favoris**
- L'état d'activation des notifications
- Le fait que vous ayez vu l'écran d'accueil (onboarding)

---

## 3. Mise en relation via WhatsApp (événements & bons plans)

Pour les événements et bons plans, l'Application propose un bouton « **Contacter sur WhatsApp** ». Lorsque vous l'utilisez, votre application WhatsApp s'ouvre avec un message pré-rempli vers l'organisateur ou le vendeur.

- Nouchi Gospel agit **uniquement comme intermédiaire** et n'est pas partie au contrat.
- La conversation et les éventuelles transactions se déroulent **directement entre vous et le tiers**, sur WhatsApp (service de **Meta**, soumis à sa propre politique de confidentialité).
- Nouchi Gospel ne collecte ni ne conserve le contenu de ces échanges.

---

## 4. Ce que nous NE collectons PAS

Nouchi Gospel **ne collecte pas** :
- Votre position GPS
- Votre carnet de contacts
- Vos photos, médias ou microphone
- Votre historique de navigation web
- Vos informations bancaires ou de paiement (l'Application est 100 % gratuite)
- Vos mots de passe

---

## 5. Base légale et finalités

Nous traitons vos données pour les finalités suivantes :

| Finalité | Base légale |
|---|---|
| Faire fonctionner l'Application (connexion, progression) | Exécution du service que vous demandez |
| Vous envoyer les notifications | Votre **consentement** (révocable à tout moment) |
| Sécuriser l'Application (App Check) | Intérêt légitime |
| Améliorer l'Application et corriger les bugs | Intérêt légitime |

**Nous ne vendons JAMAIS vos données. Nous ne les utilisons à aucune fin publicitaire.**

---

## 6. Sous-traitants et partage avec des tiers

Vos données sont traitées par les services suivants, qui appliquent leurs propres politiques de confidentialité :

| Service | Usage | Politique |
|---|---|---|
| **Google Firebase** (Auth, Firestore, Cloud Messaging, App Check, Cloud Functions) | Authentification, stockage, notifications, sécurité | https://firebase.google.com/support/privacy |
| **Google Sign-In** | Connexion optionnelle | https://policies.google.com/privacy |
| **Apple (Sign in with Apple)** | Connexion optionnelle (iOS) | https://www.apple.com/legal/privacy/ |
| **Apple App Store / Google Play** | Distribution de l'Application | Apple / Google |
| **Meta WhatsApp** | Mise en relation (si vous l'utilisez) | https://www.whatsapp.com/legal/privacy-policy |

Nous ne partageons vos données avec aucun autre tiers, sauf obligation légale.

---

## 7. Transfert de données hors de Côte d'Ivoire

Les services Google Firebase et Apple hébergent et traitent les données sur des serveurs **situés hors de Côte d'Ivoire** (notamment aux États-Unis et dans l'Union européenne). En utilisant l'Application, vous êtes informé de ce **transfert international** de vos données.

Ces transferts sont encadrés par les engagements contractuels et les mesures de sécurité de Google et d'Apple (chiffrement en transit et au repos, clauses de protection des données).

---

## 8. Stockage et sécurité

Vos données sont stockées sur les serveurs sécurisés de **Google Firebase**, qui respectent les normes internationales de sécurité (chiffrement en transit et au repos, règles d'accès Firestore restreintes par UID).

Malgré toutes les précautions, aucune transmission sur Internet n'est totalement infaillible. Nous nous engageons à appliquer les meilleures pratiques, sans pouvoir garantir une sécurité absolue.

---

## 9. Durée de conservation

- **Données de compte et de progression** : conservées tant que votre compte existe. En cas de suppression du compte, elles sont effacées sous **30 jours**.
- **Token FCM** : supprimé dès que vous désinstallez l'Application ou désactivez les notifications.
- **Données techniques** : conservées selon les durées par défaut de Firebase (jusqu'à 14 mois).

---

## 10. Vos droits

### 10.1 En Côte d'Ivoire

Conformément à la **loi n°2013-450 du 19 juin 2013 relative à la protection des données à caractère personnel**, vous disposez des droits d'**accès**, de **rectification**, d'**opposition** et de **suppression** de vos données. L'autorité de contrôle est l'**ARTCI** (Autorité de Régulation des Télécommunications/TIC de Côte d'Ivoire), auprès de laquelle vous pouvez introduire une réclamation : https://www.artci.ci

### 10.2 Union européenne (RGPD)

Si vous résidez dans l'UE, vous bénéficiez également des droits prévus par le **RGPD** : accès, rectification, effacement (droit à l'oubli), limitation, opposition et **portabilité** de vos données.

### 10.3 Comment exercer vos droits

Écrivez-nous à **roschmichel12@gmail.com**. Nous répondons sous **30 jours** maximum.

**Pour supprimer votre compte :**
1. Envoyez un e-mail à roschmichel12@gmail.com avec l'objet « Suppression de compte »
2. Indiquez l'adresse e-mail liée à votre compte
3. Nous supprimons votre compte et toutes les données associées sous 30 jours

---

## 11. Enfants

Nouchi Gospel est accessible dès **4 ans**. Nous ne collectons pas sciemment de données personnelles identifiantes auprès d'enfants de moins de 13 ans sans le consentement d'un parent. Si vous êtes parent et pensez que votre enfant nous a fourni des données, contactez-nous pour leur suppression.

---

## 12. Modifications de cette politique

Nous pouvons mettre à jour cette politique pour refléter des évolutions de l'Application ou de la législation. La date en haut du document indique la dernière version. En cas de changement important, nous vous en informerons dans l'Application ou par notification.

---

## 13. Contact

Pour toute question concernant cette politique ou vos données personnelles :

- **E-mail** : roschmichel12@gmail.com
- **Responsable du traitement** : Michel Kouakou

---

*Nouchi Gospel est une application indépendante développée avec foi et respect pour ses utilisateurs. Merci de nous faire confiance.* 🙏
