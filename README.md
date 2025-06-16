# Modelle für FUTO Spracheingabe

Möchten Sie Ihre Sprache für die Spracheingabe optimieren?

## Anforderungen

Das Modell muss whisper-tiny, whisper-base oder whisper-small auf Ihre Sprache feinabgestimmt sein. Wir unterstützen kein large, large-v2 oder large-v3, da es zu groß ist, um auf den meisten Handys zu laufen.

Damit das Modell in den Apps korrekt funktioniert, sollte es mit der [ACFT-Methode](https://github.com/futo-org/whisper-acft) feinabgestimmt werden. Dies ermöglicht eine effizientere Ausführung des Modells. Wenn Sie ein Modell in der App verwenden, das nicht mit dieser Methode feinabgestimmt ist, funktioniert es mit langen Diktaten (30s), jedoch werden kürzere Diktate (unter 15s) endlose Wiederholungen oder eine lange Verzögerung am Ende zeigen. Wenn Sie bereits ein Modell auf Ihre Sprache abgestimmt haben, aber Hilfe bei diesem Prozess benötigen, erstellen Sie bitte ein neues Issue und wir können Ihnen helfen.

## Methode

Dieses Dokument ist noch in Arbeit, weitere Details werden folgen. Wenn Sie daran interessiert sind oder dies bereits getan haben, können Sie gerne ein Issue erstellen.
