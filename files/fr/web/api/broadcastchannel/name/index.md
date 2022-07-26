---
title: BroadcastChannel.name
slug: Web/API/BroadcastChannel/name
page-type: web-api-instance-property
translation_of: Web/API/BroadcastChannel/name
browser-compat: api.BroadcastChannel.name
---
{{APIRef("BroadCastChannel API")}}

La propriété en lecture seule **`BroadcastChannel.name`** retourne une chaîne qui identifie de manière unique le canal par son nom. Ce nom est passé au constructeur [`BroadcastChannel()`](/fr/docs/Web/API/BroadcastChannel/BroadcastChannel) lors de la création et est par conséquent en lecture seule.

{{AvailableInWorkers}}

## Valeurs

Une chaîne

## Exemples

```js
// Connexion à un canal
const canal = new BroadcastChannel('canal_test');

// D'autres traitements (tel que postMessage, …)

// Affiche la propriété name du canal dans la console
console.log(canal.name); // "canal_test"

// Lorsque les traitements sont terminés, déconnexion
canal.close();
```

## Spécifications

{{Specifications}}

## Compatibilité des navigateurs

{{Compat}}

## Voir aussi

- [`BroadcastChannel`](/fr/docs/Web/API/BroadcastChannel), l'interface à laquelle elle se rapporte.