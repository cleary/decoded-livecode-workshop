![DECODED Banner](images/banner_estuary.png)

# Command Quick Reference

![Estuary Terminal](images/estuary_terminal.png)

## View Modifiers

*See what views are available*
```
!listviews
```

---

*choose a view to display locally (your pc only) from above output*
```
!presetview n
```

---

*set the current view for all users in the ensemble*
```
!publishview def
```

---

 *return to the default view on your local display*
```
!presetview def
```

---

*see what code generated the current view*
```
!dumpview
```

---

*list all samples*
```
!localview audiomap
```

---

*show visuals only, on the local display*
```
!localview []
```

---

*display `iframes` in cells, checkout vdo.ninja*
```
!localview $ grid 2 2 [iFrame "https://en.wikipedia.org/wiki/4hero",code 0 0,code 1 0,iFrame "https://en.wikipedia.org/wiki/4hero"]
```

---

## In-Jam Functions

*get tempo*
```
!showtempo
```

---

*set tempo in cycles per second, between 0-1 is a safe range*
```
!setcps x.y
```

---

*[add your own (hosted) samples](https://github.com/dktr0/estuary/wiki#adding-sound-files-to-estuarywebdirt-on-the-fly-early-august-2021)*

```
!reslist "https://your.hosted.samples/resources.json"
```

---

*show what external resources have been loaded*
```
!showresources
```

---

 *return to initial state of estuary server provided resources*
```
!defaultresources
```

---

 *remove all resources, incl estuary defaults*
```
!clearresources
```

**[Copyright](/COPYRIGHT.md)**
