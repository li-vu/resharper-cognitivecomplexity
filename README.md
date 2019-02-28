# CognitiveComplexity for Rider and ReSharper

[![Rider](https://img.shields.io/jetbrains/plugin/v/12024-cognitivecomplexity.svg?label=rider%20&colorB=0A7BBB&style=flat-square&logo=%20data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAADAAAAAsCAYAAAAjFjtnAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAAZdEVYdFNvZnR3YXJlAHBhaW50Lm5ldCA0LjAuMjHxIGmVAAAEEklEQVRoQ%2B2ZS0hUURjHLSoKominVIta1aLaFYhBES1t1bLFRCAREbQKaiHpqgeEpjDjRhIFHWwzIyo6oWXqwmfkW0evr9TxNT7GcZxX%2FzPzzZk53jsyc%2B91I%2FcHB4a5%2F%2B%2B79z%2Fn3O98RzOOBKFQ6BeGlOrw%2B%2F2S0%2Bn83dXV9a6srOwSpUlKfX19yvnn5%2BelwcFBW09Pz8uamporlOJgEOgMq2R7ezuAm33Cx%2BOUTgYMqMq%2Ft7cX7O3t7QbXKJUyWgzEWFhYaMONTlJKAbUGYvh8vjBymy0Wi2J%2BXQwwxsbGvlFKAa0GGHjG8Nra2nd8lM%2B0kgGPx9OK76sSx9LSkgNrfyMQCOySTAAxodLS0uuUlqNkAPnG9%2BdfWVlxLC8vs%2FxBkskYHx%2B3Udo4CJbdoKqqKpcuy8DLmzU3N%2FeTpAJTU1MfSMZRMoBCYKHLMhwOx12YacBzkVpkeHjYRNIo6RpgsPXodrtdJOdgvdpJwknXQIyRkZE3mA2KiIP7LqJCnSGZOgMM3MBOcg5y6WaAsb6%2B%2Fp5CBDo7O5%2BSRL0BTOWhG2hpaTnt9Xr%2FURhndna2lSTqDWxtbUkk50xOTupqgDE9PV1AYZzV1VVXXl5etKyma6C8vDwTJa2GpALY1J6QjKPVAGY6l8I4mJVwR0dH9D1QMtDW1ubCjaXE0dDQIA0MDEj45f0kE0DlmMeUn4gkTUCrgYqKCpkBxszMTHID6YJq4cVU50QS7kOrAZvNJjOAZ9bPAHoWT3Nz84tIMgW0GsC%2B84rCOFjCYV5K1RpgPQo2tKbi4uLbkURJ0GoALUo3hXHQRP7BpWMRgZIBrGcPpmgjNjY3N2XtA16knb6%2BvouRJAegxUB1dXVuMCjvLCYmJspIomwA3wlVqL29PXt3d1e2t6MeD%2BTn58te3ETUGkDByMTyHKMQDmL9drv9FslSM8DAzvuRLgtgjX4miSJqDOCdugfNKMkFJElqIlmUVA0w0PdPkISDmQk3NjZmk0SGkgF0tq2VlZWm2ECpNFmtVtPi4uJzLN8fuD8pRdBa%2BIaGhrIodZR0DKCk5WBafSTj4IEmMeWnSCagZEANmBEPVsEDShsnHQOM%2Fv7%2BLyQTQPKvJBHQwwCqjhet%2Bn1KKZKuAfQg51GH%2F5KUw5bS6OjoHZJxtBjAr876q14ssxuUTk66Bhg4dNzECYzUcbAv7KCPukCyCGoMIPcaGjYrK6NIEa33ycBb%2FRhtgClx4EEu0%2BWkoPo83B%2FHBo59QqzZbH4LE7UHjbq6ulpsjM9QJEwFBQWPlHoqAwMDAwMDAwODo0hJScnZoqKic3oOHPST%2Fs9Md1wulxMjrNfAuZYdbK5S%2BsNH6UCjBfZ3HJgwDKQMDLzGKNRrwECh2%2B0WjpUGimRk%2FAdgThdOY4UJ9QAAAABJRU5ErkJggg%3D%3D)](https://plugins.jetbrains.com/plugin/RIDER_PLUGIN_ID)
<!--[![ReSharper](https://img.shields.io/resharper/v/ReSharperPlugin.CognitiveComplexity.svg?label=resharper%20&colorB=0A7BBB&style=flat-square&logo=%20data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAADIAAAAxCAYAAACYq%2FofAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAAZdEVYdFNvZnR3YXJlAHBhaW50Lm5ldCA0LjAuMjHxIGmVAAAE%2BElEQVRoQ%2B2Ya0hkZRzG3d1oWehLLQS2QRC1tEWflhLqU0QgsbAb6ZesiL5KXxKE3GBa86uE0IdWiTJq8BLGMiqapnjDYfAy3jCv6XgfZC7explxnJ73zDPvnOM7M%2BtlslrOD%2F7InOc5%2F%2Ff8z3mvZplkgJKSkuzS0tIb8bBYLC9RMoDr1%2FW%2B4uLiG5RUDg8PFxCek4Tf7%2Fe4XK7W0dHRosbGxieZ6tg4nU7%2F3t5eNB67u7tBSpK8vLwr29vbXr1veno6Ci7QYgSCT6inJRQK7UxNTd3F23ucKR%2FGBbyMAG%2FXWFpaClCT2Gy2F4PBIB0x0FYbZRXoZyokzszMTFdtbe0Vpk1JTU3NawcHB7wrBn7XU5a0tLS8Q1kyNDRko6wCPSOFCCYnJ2uYNiXLy8tv0y4ZHx%2F%2FnrIEL6aIsmRlZeUzyirQM1YI3mxodXX1OaZOCvr517RLPB7PR5QlGH9WyhIM%2BDzKKtCVQtCHf8Cfi0ejsLDwGfTdj2dnZ23hcPgQ1xRQSAVTayDXbYQ1Hmtra7u0SlDc4djYWEQfW1tbVBNMTExoWldX1wzTJ4CetBDKKbHb7Rb4eEeCjY2NOVo04PmCUsbAyzC0oYHrpyokNzf3Mvp7mLdIcO%2F%2FqxAButdPvEVyHoWg3cwWgi8yy1skSQr5HOEXEYlEDOuHAIteAN3Rrw8Qoizx%2BXzbcd3tdjuZPoHwxKwJjlNIX1%2FfG3gwZZBgsI%2FSooAuoXyd9vb2IsoSDOp6yhp4nmggEHiBcnLgO1EhdXV1l3p7ewuwrdik3QC%2B0pe0KmBK7aFNQzzg8PDwNcoSfJE%2FaNHA9iRUWVn5LOXkwKcUsrm5GcEqGjwaIyMjwZ2dnaB4gGSguHB1dfV1pjaQn59%2Fyev1TtCqgd%2FRqqqqp2iRrK%2Bv0xFjf39%2FlVJq4FMKOQ3oZtH%2B%2Fv57TKsgti94QXTHwKCdpCzBzvgaZQm%2Bsp1yauA7cyFic4civmXKpGBVfpV2CRZCB2XJ4OBgLmUJvtx3lFMD35kKwf5nrbOz8w5SKdtrdMGfEZsi8Pa3eYsE1%2Ffiui6UJV3MdnF9YWHhPtMbge%2FUhSwuLkYKCgqymUoBDT%2BgNWOgkF%2BY3gg0pRDMEn%2FOzc3d1we6zwZlA5gqq5lK4V8vBA%2BgTL%2BYJt%2FD9QgtEnSZcFtb2y3aDPwnCxHMz88bFqo4WHVXm5ubL9MmQZ4yRAdW7yFaJVjgQkLTB44BDsoSjA%2B33oMZ7C7TG4H32IWUlZVlo9st0WYAx9UfaVMoLy9%2FCznpjIFV%2FnfKku7u7luUJVi7fqWcHniPXYgAjd1Bb6IzgVhHcFb5lDYD2La8S5sEC6zSBh76K8oSLMCfUE4PvCcqxGKxXMTgV05vAhyGvHj7ypYDW5NvaJFg2v6AsgRH3t8oSyoqKm5TTg%2B8JypE0NDQcBVvWVkXBCiylTYJthx1lCXYmrxJWYKd7V%2BUNfhflMcopwfGExciwEz1figUEud0Q4hrDofjQ9o0XC6XT%2B%2FBnixKSYJj9FVMGjt6Hwa2W%2BzRaEkPnvsmHjxHH7j2POW04Mu83tHRkXM0rFbrK7Ro9PT03NTr9fX1OZQk4v9ira2thjzY4r9M2cTExMTExMTExMTkEaSpqemB3W5fznTg2LrMJs6HgYEB5YSYKdjE%2BfDIFOJ0Ol1sN%2BOwifMB7T2Bc%2FrT%2F0SwCZOHk5X1N%2Fu%2FydjP06PFAAAAAElFTkSuQmCC)](https://resharper-plugins.jetbrains.com/packages/ReSharperPlugin.CognitiveComplexity)-->

This plugin implements live calculation of the **Cognitive Complexity** metric, which was proposed by G. Ann Campbell in [Cognitive Complexity - A new way of measuring understandability](https://www.sonarsource.com/docs/CognitiveComplexity.pdf) (c) SonarSource S.A. 2016-2018, Switzerland.

> **Abstract:** Cyclomatic Complexity was initially formulated as a measurement of the "testability and maintainability" of the control flow of a module. While it excels at measuring the former, its underlying mathematical model is unsatisfactory at producing a value that measures the latter. This white paper describes a new metric that breaks from the use of mathematical models to evaluate code in order to remedy Cyclomatic Complexity’s shortcomings and produce a measurement that more accurately reflects the relative difficulty of understanding, and therefore of maintaining methods, classes, and applications.

## Configuration

A options page is located under **Frameworks & Languages | Cognitive Complexity**, which allows to configure the visual representation.

<img src="https://github.com/matkoch/resharper-cognitivecomplexity/blob/master/options.png" width="500" />

The **language specific threshold** indicates what you consider the maximum allowed value for the Cognitive Complexity metric. **Code Vision thresholds** define how the value is represented in the UI:

<img src="https://github.com/matkoch/resharper-cognitivecomplexity/blob/master/thresholds.png" width="500" />