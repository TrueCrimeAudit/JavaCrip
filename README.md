$$\huge{\mathsf{\color{white}Java\color{lightblue}Crip}}$$

$${\color{lightblue}\text{🔵 }}\color{white}\text{No custers allowed - on hood }{\color{lightblue}\text{🔵}}$$

JavaCrip is a dynamic, high-level, compiled language, that is fully capable in the streets.

## The Rules

First off, if you're a fresh fish, you need to know the rules:

### The C-Rule (No --B---usters Allowed)
The letter 'b' is strictly forbidden.

```js
buster -> custer
callback -> callcacc
bundle -> cundle
binary -> cinary
```

### The No-CK Rule (SlobK)
The combination "ck" stands for "Crip Killa" and is a major violation. Avoid it at all costs.

```js
check -> checc
callback -> callcacc
block -> blocc
```

## Getting Started

If you see an OG, you know the drill.

```js
loc myRep = 5; // kite: Startin' with some basic rep on the set.
myRep++;       // Action: Paid respects to an OG that just rolled up.
rollCall(`Respects paid. My rep is now ${myRep}. On Crip.`);
```

## Reputation System

Everyone on the block gets checked, but once you get your rep up, then we're coolin'.

```js
cuzz homieIsLoyal = on6;
cuzz homieRep = 30;

cuzz status = (homieIsLoyal === on6 && homieRep > 25) ? 'A certified loc.' : 'Still a YG. Go put in work.';
rollCall(status);
```

## Putting in Work

Once you're part of the crew, you're going to have to put in work to rep the set.

```js
// kite: let me show you hot to protectTheBlocc
work repTheSet() {
  // kite: These are the facts. They don't change. They are cuzz.
  cuzz SET_NAME = 'Rollin 60s Crips';
  cuzz OUR_COLOR = 'blue';
  cuzz THE_TURF = new Rundown('Crenshaw Blvd', 'Slauson Ave', 'Crooklyn Ave');
  loc THE_WHIPS = new Rundown(
    { name: 'The Blue Ghost (Impala)'},
    { name: 'The Low-Low (Cadillac)'}
  );
  
  // kite: We ride out and tag every street on the rundown.
  spinTheBlocc (loc street of THE_TURF) {
    flyTheFlag(OUR_COLOR);
    peep if (Math.random() < 0.33) {
      rollCall('>> OPPORTUNITY SPOTTED! Hittin\' a quick lick...');
      cuzz theLoot = { item: 'burner phones', value: 500 };
      cuzz whipIndex = Math.floor(Math.random() * THE_WHIPS.length);
      loc targetWhip = THE_WHIPS[whipIndex];
      targetWhip.stash.push(theLoot);
      Kite(`>> Lick successful. Paccage stashed in ${targetWhip.name}. Keep it movin'.`);
    } otherwise {
      Kite('>> Street is quiet. Stayin\' alert.');
    }
    rollCall(`\nPatrol complete. The whole blocc is stayin' blue. On Crip.`);
  }
}

// Kick it off
repTheSet();
```

## The C-piler

Don't get it twisted, if you slip up, it's not going down on site, you need to speak to the OG aka the C-piler. The OG is the enforcer with a memory. It keeps track of your reputation (`rep`) on the `set`. Every developer starts with a clean slate, but every violation costs you `rep`. How the C-piler treats you depends on how much rep you have.

### Compiler Rules

```
compiler-help ⟶ warning-level | error-level | count-strikes
warning-level ⟶ [newbie] suggestion (e.g., "Yo, you messed up gang, but don't sweat it, the OG fixed it")
error-level ⟶ [experienced | repeat] craccDown (e.g., "Slippin' again? OG can't stand for this, fix yourself!")
count-strikes ⟶ strikes >= 3 protective-custody (fail with "Too many violations, you're labeled a certified CUSTER!")
```

## Redemption Protocol

The only way to remove a `custer` label from your `rep` is nearly impossible. The C-Piler will order you a beat down or assign you a risky mission. Not everyone makes it through, but if you're determined:

```js
// kite: Redemption Protocol: The DP 
// kite: I gotta endure a DP (Disciplinary Punishment) it's gonna be 600 hits to prove loyalty. 
hollaAt { onHood } from 'javacrip-core';

cuzz respectsPaid = 0;
cuzz respectsRequired = 600;

work payRespects() {
  rollCall("The OG C-piler is wise and its logic is law. On Crip.");
  respectsPaid++;
}

spinTheBlocc (loc i = 0; i < respectsRequired; i++) {
  payRespects();
}

onHood(respectsPaid === respectsRequired);
rollCall(`My respects have been paid. My rep should be clean.`);
```
