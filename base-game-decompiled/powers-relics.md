# Powers, Relics, Orbs & Potions — Class Reference

| Class | Namespace | Bases | Methods | Fields | Source |
|---|---|---|---|---|---|
| `OrbQueue` | `MegaCrit.Sts2.Core.Entities.Orbs` |  | `Clear()`, `AddCapacity(int capacity)`, `RemoveCapacity(int capacity)`, `TryEnqueue(OrbModel orb)`, `Remove(OrbModel orb)`, `Insert(int idx, OrbModel orb)`, `BeforeTurnEnd(PlayerChoiceContext choiceContext)`, `AfterTurnStart(PlayerChoiceContext choiceContext)`, `SmallWait()` | `Orbs`, `Capacity` | `MegaCrit.Sts2.Core.Entities.Orbs/OrbQueue.cs` |
| `PotionBodyExtensions` | `MegaCrit.Sts2.Core.Entities.Potions` |  | `GetBodyPath(PotionBody body)`, `GetGradientPath(PotionBody body)`, `GetJuicePath(PotionBody body)`, `GetOverlayPath(PotionBody body, PotionOverlay overlay)` |  | `MegaCrit.Sts2.Core.Entities.Potions/PotionBodyExtensions.cs` |
| `PotionProcureResult` | `MegaCrit.Sts2.Core.Entities.Potions` |  |  |  | `MegaCrit.Sts2.Core.Entities.Potions/PotionProcureResult.cs` |
| `PotionRarityExtensions` | `MegaCrit.Sts2.Core.Entities.Potions` |  | `ToLocString(PotionRarity potionRarity)` |  | `MegaCrit.Sts2.Core.Entities.Potions/PotionRarityExtensions.cs` |
