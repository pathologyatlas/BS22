







```
r language BS22, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis ring mitosis, taxane treatment TR, echo = (language == "TR")
## BS22 - ring mitosis, taxane treatment {#sec-BS22 }
```


```
asis ring mitosis, taxane treatment EN, echo = (language == "EN")
## BS22 - ring mitosis, taxane treatment {#sec-BS22 }
```






```
r BS22 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS22-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS22/HE.html",
  file = "./screenshots/BS22-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/BS22/HE.html](https://images.patolojiatlasi.com/BS22/HE.html)





```
asis, echo = (language == "TR")

**ring mitosis, taxane treatment**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS22-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS22/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS22/HE.html)
```

```
asis, echo = (language == "EN")

**ring mitosis, taxane treatment**

[![Click for Full Screen WSI](./screenshots/BS22-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS22/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS22/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS22/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS22/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

ring mitosis, taxane treatment

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

ring mitosis, taxane treatment

:::

```









:::::









