| Route                        | Urban planner | Developer | Resident | Visitor |
| ---------------------------- | ------------: | --------: | -------: | ------: |
| GET /documents               |            ✅ |        ✅ |       ✅ |      ✅ |
| GET /documents/{id}          |            ✅ |        ✅ |       ✅ |      ✅ |
| POST /documents              |            ✅ |        ❌ |       ❌ |      ❌ |
| PATCH /documents/{id}        |            ✅ |        ❌ |       ❌ |      ❌ |
| DELETE /documents/{id}       |            ✅ |        ❌ |       ❌ |      ❌ |
| GET /documents/{id}/links    |            ✅ |        ✅ |       ✅ |      ✅ |
| PUT /documents/{id}/links    |            ✅ |        ❌ |       ❌ |      ❌ |
| DELETE /documents/{id}/links |            ✅ |        ❌ |       ❌ |      ❌ |
| GET /uploads                 |            ✅ |        ✅ |       ✅ |      ✅ |
| GET /uploads/{id}            |            ✅ |        ✅ |       ✅ |      ✅ |
| POST /uploads                |            ✅ |        ❌ |       ❌ |      ❌ |
| PATCH /uploads/{id}          |            ✅ |        ❌ |       ❌ |      ❌ |
| DELETE /uploads/{id}         |            ✅ |        ❌ |       ❌ |      ❌ |
| POST /sessions               |            ❌ |        ❌ |       ❌ |      ✅ |
| GET /sessions/current        |            ✅ |        ✅ |       ✅ |      ❌ |
| DELETE /sessions/current     |            ✅ |        ✅ |       ✅ |      ❌ |
| POST /users                  |            ❌ |        ❌ |       ❌ |      ✅ |