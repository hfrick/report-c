proj_opts <- eval(parse(text = read.dcf("DESCRIPTION", "Settings/R")))
if (is.list(proj_opts)) options(proj_opts)

if ("pkgload" %in% rownames(utils::installed.packages())) {
  pkgload::load_all()
}
