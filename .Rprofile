setwd("~/content")
setHook("rstudio.sessionInit", function(newSession) {
  if (newSession)
    rstudioapi::filesPaneNavigate(getwd())
}, action = "append")

