# KPI definitions

All metrics recalculate using the filtered synthetic records.

| KPI | Definition |
|---|---|
| Total handover entries | Number of filtered rows |
| Negative entries | Number of filtered rows with Change Type = Negative |
| Negative share | Negative entries / total filtered entries × 100; zero if denominator zero |
| Patients needing review | Number of distinct demonstration patient codes whose latest filtered row is Negative |
| Entries by shift | Count grouped by AM / PM |
| Entries by role | Count grouped by Nurse / Support Worker; **not** a staff performance measure |
| Daily handover entries | Count grouped by date |

**Latest** is the final matching record in date/shift order; without time-of-day timestamps, intra-shift ordering is ambiguous. Review flags are illustrative, not clinical risk assessments.
