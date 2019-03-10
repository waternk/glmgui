
<!-- README.md is generated from README.Rmd. Please edit that file -->

# glmgui

Mirror of the `glmgui` package: <https://doi.org/10.5281/zenodo.2025865>

## Usage

``` r
library(glmgui)

glmGUI()
```

<details>

<summary>devtools::check()
    output</summary>

    #> ── Building ────────────────────────────────────────────────────────────────────────── glmgui ──
    #> Setting env vars:
    #> ● CFLAGS    : -Wall -pedantic
    #> ● CXXFLAGS  : -Wall -pedantic
    #> ● CXX11FLAGS: -Wall -pedantic
    #> ────────────────────────────────────────────────────────────────────────────────────────────────
    #>   
       checking for file ‘/home/jose/R/scripts/glmgui/DESCRIPTION’ ...
      
    ✔  checking for file ‘/home/jose/R/scripts/glmgui/DESCRIPTION’
    #> 
      
    ─  preparing ‘glmgui’:
    #> 
      
       checking DESCRIPTION meta-information ...
      
    ✔  checking DESCRIPTION meta-information
    #> 
      
    ─  checking for LF line-endings in source and make files and shell scripts
    #> 
      
    ─  checking for empty or unneeded directories
    #> ─  looking to see if a ‘data/datalist’ file should be added
    #> 
      
    ─  building ‘glmgui_1.0.tar.gz’
    #> 
      
       
    #> 
    ── Checking ────────────────────────────────────────────────────────────────────────── glmgui ──
    #> Setting env vars:
    #> ● _R_CHECK_CRAN_INCOMING_USE_ASPELL_: TRUE
    #> ● _R_CHECK_CRAN_INCOMING_REMOTE_    : FALSE
    #> ● _R_CHECK_CRAN_INCOMING_           : FALSE
    #> ● _R_CHECK_FORCE_SUGGESTS_          : FALSE
    #> ── R CMD check ────────────────────────────────────────────────────────────
    #>   
    ─  using log directory ‘/tmp/Rtmp13TM60/glmgui.Rcheck’
    #> 
      
    ─  using R version 3.5.2 (2018-12-20)
    #> ─  using platform: x86_64-pc-linux-gnu (64-bit)
    #> ─  using session charset: UTF-8
    #> 
      
    ─  using options ‘--no-manual --as-cran’
    #> 
      
    ✔  checking for file ‘glmgui/DESCRIPTION’
    #> ─  checking extension type ... Package
    #> ─  this is package ‘glmgui’ version ‘1.0’
    #>    checking package namespace information ...
      
    ✔  checking package namespace information
    #>    checking package dependencies ...
      
    ✔  checking package dependencies (1.2s)
    #> 
      
    ✔  checking if this is a source package
    #> 
      
    ✔  checking if there is a namespace
    #> 
      
       checking for executable files ...
      
    ✔  checking for executable files
    #> 
      
    ✔  checking for hidden files and directories
    #>    checking for portable file names ...
      
    ✔  checking for portable file names
    #> ✔  checking for sufficient/correct file permissions
    #> 
      
    ✔  checking serialization versions
    #>    checking whether package ‘glmgui’ can be installed ...
      
    ✔  checking whether package ‘glmgui’ can be installed (2.3s)
    #> 
      
       checking installed package size ...
      
    ✔  checking installed package size
    #> 
      
       checking package directory ...
      
    ✔  checking package directory
    #>    checking DESCRIPTION meta-information ...
      
    ✔  checking DESCRIPTION meta-information
    #> 
      
    ✔  checking top-level files
    #> ✔  checking for left-over files
    #> ✔  checking index information
    #>    checking package subdirectories ...
      
    ✔  checking package subdirectories
    #> 
      
       checking R files for non-ASCII characters ...
      
    ✔  checking R files for non-ASCII characters
    #> 
      
       checking R files for syntax errors ...
      
    ✔  checking R files for syntax errors
    #> 
      
       checking whether the package can be loaded ...
      
    ✔  checking whether the package can be loaded
    #> 
      
       checking whether the package can be loaded with stated dependencies ...
      
    ✔  checking whether the package can be loaded with stated dependencies
    #> 
      
       checking whether the package can be unloaded cleanly ...
      
    ✔  checking whether the package can be unloaded cleanly
    #> 
      
       checking whether the namespace can be loaded with stated dependencies ...
      
    ✔  checking whether the namespace can be loaded with stated dependencies
    #> 
      
       checking whether the namespace can be unloaded cleanly ...
      
    ✔  checking whether the namespace can be unloaded cleanly
    #> 
      
       checking loading without being on the library search path ...
      
    ✔  checking loading without being on the library search path
    #> 
      
       checking dependencies in R code ...
      
    W  checking dependencies in R code
    #> 
      
       'library' or 'require' calls not declared from:
    #>      ‘GLMr’ ‘glmtools’
    #>    'library' or 'require' calls in package code:
    #>      ‘GLMr’ ‘glmtools’
    #>      Please use :: or requireNamespace() instead.
    #>      See section 'Suggested packages' in the 'Writing R Extensions' manual.
    #>    checking S3 generic/method consistency ...
      
    ✔  checking S3 generic/method consistency (458ms)
    #> 
      
       checking replacement functions ...
      
    ✔  checking replacement functions
    #> 
      
       checking foreign function calls ...
      
    ✔  checking foreign function calls
    #> 
      
       checking R code for possible problems ...
      
    N  checking R code for possible problems (5.7s)
    #> 
      
       build_model: no visible binding for '<<-' assignment to
    #>      ‘label_status_build’
    #>    build_model: no visible binding for global variable
    #>      ‘label_status_build’
    #>    build_model: no visible global function definition for ‘svalue<-’
    #>    build_model: no visible binding for global variable ‘List_values’
    #>    build_model: no visible global function definition for ‘svalue’
    #>    build_model: no visible binding for global variable ‘button_build’
    #>    build_model: no visible binding for '<<-' assignment to ‘dir_output’
    #>    build_model: no visible binding for global variable ‘dir_output’
    #>    build_model: no visible global function definition for ‘read_nml’
    #>    build_model: no visible global function definition for ‘get_nml_value’
    #>    build_model: no visible global function definition for ‘set_nml’
    #>    build_model: no visible binding for global variable ‘List_parameter’
    #>    build_model: no visible global function definition for ‘write_nml’
    #>    build_model: no visible global function definition for ‘run_glm’
    #>    build_model: no visible binding for global variable
    #>      ‘checkbox_Level_plot’
    #>    build_model: no visible binding for global variable
    #>      ‘checkbox_Level_rmse’
    #>    build_model: no visible binding for global variable ‘dir_field_level’
    #>    build_model: no visible binding for global variable
    #>      ‘checkbox_Temp_plot’
    #>    build_model: no visible binding for global variable
    #>      ‘checkbox_Temp_rmse’
    #>    build_model: no visible global function definition for
    #>      ‘compare_to_field’
    #>    build_model: no visible binding for global variable ‘dir_field_temp’
    #>    build_model: no visible global function definition for ‘gwindow’
    #>    build_model: no visible global function definition for ‘ggraphics’
    #>    build_model: no visible global function definition for ‘dev.cur’
    #>    build_model: no visible global function definition for ‘plot’
    #>    build_model: no visible binding for global variable
    #>      ‘checkbox_Temp_plot2’
    #>    build_model: no visible binding for global variable
    #>      ‘checkbox_Temp_plot3’
    #>    build_model: no visible binding for global variable
    #>      ‘checkbox_Temp_plot4’
    #> build_model: no visible binding for '<<-' 
      
       build_model: no visible binding for '<<-' assignment to ‘button_build’
    #>    calculate_SI_value: no visible global function definition for ‘run_glm’
    #>    calculate_SI_value: no visible global function definition for
    #>      ‘svalue<-’
    #>    calculate_SI_value: no visible binding for '<<-' assignment to
    #>      ‘dir_output’
    #>    calculate_SI_value: no visible binding for global variable ‘dir_output’
    #>    calculate_SI_value: no visible global function definition for
    #>      ‘read_nml’
    #>    calculate_SI_value: no visible global function definition for
    #>      ‘get_nml_value’
    #>    calculate_SI_value: no visible global function definition for ‘svalue’
    #>    calculate_SI_value: no visible global function definition for ‘set_nml’
    #>    calculate_SI_value: no visible global function definition for
    #>      ‘write_nml’
    #>    calculate_SI_value: no visible global function definition for
    #>      ‘compare_to_field’
    #>    calculate_SI_value: no visible binding for global variable
    #>      ‘dir_field_temp’
    #>    calculate_SI_value: no visible binding for global variable
    #>      ‘dir_field_level’
    #>    calculate_SI_value: no visible global function definition for
    #>      ‘write.csv’
    #>    calculate_SI_value: no visible global function definition for ‘gwindow’
    #>    calculate_SI_value: no visible global function definition for
    #>      ‘ggraphics’
    #>    calculate_SI_value: no visible global function definition for ‘dev.cur’
    #>    calculate_SI_value: no visible global function definition for ‘par’
    #>    calculate_SI_value: no visible global function definition for ‘barplot’
    #>    calculate_aov: no visible global function definition for ‘stack’
    #>    calculate_aov: no visible global function definition for ‘aov’
    #>    calculate_auto_kalib: no visible global function definition for
    #>      ‘run_glm’
    #>    calculate_auto_kalib: no visible global function definition for
    #>      ‘svalue<-’
    #>    calculate_auto_kalib: no visible binding for '<<-' assignment to
    #>      ‘dir_output’
    #>    calculate_auto_kalib: no visible binding for global variable
    #>      ‘dir_output’
    #>    calculate_auto_kalib: no visible global function definition for
    #>      ‘read_nml’
    #>    calculate_auto_kalib: no visible global function definition for
    #>      ‘get_nml_value’
    #> calculate_auto_kalib: no vis
      
       calculate_auto_kalib: no visible binding for global variable
    #>      ‘but_cal_si_auto’
    #>    calculate_auto_kalib: no visible global function definition for
    #>      ‘set_nml’
    #>    calculate_auto_kalib: no visible global function definition for
    #>      ‘write_nml’
    #>    calculate_auto_kalib: no visible global function definition for
    #>      ‘compare_to_field’
    #>    calculate_auto_kalib: no visible binding for global variable
    #>      ‘dir_field_temp’
    #>    calculate_auto_kalib: no visible binding for global variable
    #>      ‘dir_field_level’
    #>    calculate_auto_kalib: no visible global function definition for
    #>      ‘write.table’
    #>    calculate_needed_time: no visible global function definition for
    #>      ‘svalue<-’
    #>    calculate_needed_time2: no visible global function definition for
    #>      ‘svalue<-’
    #>    check_data_connection: no visible global function definition for
    #>      ‘read_nml’
    #>    check_data_connection: no visible global function definition for
    #>      ‘svalue<-’
    #>    check_data_connection: no visible global function definition for
    #>      ‘get_nml_value’
    #>    check_data_connection: no visible binding for '<<-' assignment to
    #>      ‘button_confi’
    #>    check_data_connection: no visible binding for global variable
    #>      ‘button_confi’
    #>    check_data_connection: no visible global function definition for
    #>      ‘enabled<-’
    #>    check_data_connection: no visible binding for '<<-' assignment to
    #>      ‘button_set_parameter’
    #>    check_data_connection: no visible binding for global variable
    #>      ‘button_set_parameter’
    #>    check_data_connection: no visible binding for '<<-' assignment to
    #>      ‘button_build’
    #>    check_data_connection: no visible binding for global variable
    #>      ‘button_build’
    #>    check_data_connection: no visible binding for '<<-' assignment to
    #>      ‘button_cal_SI_value’
    #>    check_data_connection: no visible binding for global variable
    #>      ‘button_cal_SI_value’
    #>    check_data_connection: no visible binding for '<<-' assignment to
    #>      ‘button_field_level’
    #>    check_data_connection: no visible binding for global variable
    #>      ‘button_field_level’
    #>    check_data_connection: no visible binding for '<<-' assignment to
    #>      ‘button_field_temp’
    #> check_data_connection: no visible binding for global
      
       check_data_connection: no visible binding for global variable
    #>      ‘button_field_temp’
    #>    check_data_connection: no visible binding for '<<-' assignment to
    #>      ‘button_autocalib’
    #>    check_data_connection: no visible binding for global variable
    #>      ‘button_autocalib’
    #>    check_data_connection: no visible binding for '<<-' assignment to ‘l’
    #>    check_data_connection: no visible binding for '<<-' assignment to ‘k’
    #>    check_data_connection: no visible binding for global variable ‘l’
    #>    check_data_connection: no visible binding for global variable ‘k’
    #>    check_data_connection: no visible binding for '<<-' assignment to
    #>      ‘dir_meteo’
    #>    check_data_connection: no visible binding for '<<-' assignment to
    #>      ‘arg_meteo’
    #>    check_data_connection: no visible binding for global variable
    #>      ‘dir_meteo’
    #>    check_data_connection: no visible binding for '<<-' assignment to
    #>      ‘label_met_data’
    #>    check_data_connection: no visible binding for global variable
    #>      ‘label_met_data’
    #>    check_data_connection: no visible binding for '<<-' assignment to
    #>      ‘multi_inflow’
    #>    check_data_connection: no visible binding for global variable
    #>      ‘multi_inflow’
    #>    check_data_connection: no visible binding for '<<-' assignment to
    #>      ‘label_inflow_data’
    #>    check_data_connection: no visible binding for global variable
    #>      ‘label_inflow_data’
    #>    check_data_connection: no visible binding for '<<-' assignment to
    #>      ‘arg_inflow’
    #>    check_data_connection: no visible binding for '<<-' assignment to
    #>      ‘dir_inflow’
    #>    check_data_connection: no visible binding for global variable
    #>      ‘dir_inflow’
    #>    check_data_connection: no visible binding for '<<-' assignment to
    #>      ‘multi_outflow’
    #>    check_data_connection: no visible binding for global variable
    #>      ‘multi_outflow’
    #>    check_data_connection: no visible binding for '<<-' assignment to
    #>      ‘label_outflow_data’
    #>    check_data_connection: no visible binding for global variable
    #>      ‘label_outflow_data’
    #>    check_data_connection: no visible binding for '<<-' assignment to
    #>      ‘dir_outflow’
    #>    check_data_connection: no visible binding for global variable
    #>      ‘dir_outflow’
    #> get_dataframe_Level_Lake: no visible global function 
      
       get_dataframe_Level_Lake: no visible global function definition for
    #>      ‘read.csv’
    #>    get_dataframe_Level_Lake: no visible global function definition for
    #>      ‘na.omit’
    #>    get_parameter: no visible global function definition for ‘read_nml’
    #>    get_parameter: no visible global function definition for ‘gwindow’
    #>    get_parameter: no visible global function definition for ‘ggroup’
    #>    get_parameter: no visible global function definition for ‘glabel’
    #>    get_parameter: no visible global function definition for ‘font<-’
    #>    get_parameter: no visible global function definition for
    #>      ‘get_nml_value’
    #>    get_parameter: no visible global function definition for ‘gedit’
    #>    get_parameter: no visible global function definition for ‘gseparator’
    #>    get_parameter: no visible global function definition for ‘visible<-’
    #>    get_pre_list_of_default_values: no visible binding for global variable
    #>      ‘workspace’
    #>    get_pre_list_of_default_values: no visible global function definition
    #>      for ‘read_nml’
    #>    get_pre_list_of_default_values: no visible global function definition
    #>      for ‘svalue’
    #>    get_pre_list_of_default_values: no visible global function definition
    #>      for ‘svalue<-’
    #>    get_pre_list_of_default_values: no visible global function definition
    #>      for ‘get_nml_value’
    #>    glmGUI: no visible global function definition for ‘install.packages’
    #>    set_cali_boundary: no visible global function definition for ‘gwindow’
    #>    set_cali_boundary: no visible global function definition for ‘gframe’
    #>    set_cali_boundary: no visible global function definition for ‘ggroup’
    #>    set_cali_boundary: no visible global function definition for ‘glabel’
    #>    set_cali_boundary: no visible global function definition for
    #>      ‘gcombobox’
    #>    set_cali_boundary : <anonymous>: no visible global function definition
    #>      for ‘svalue’
    #>    set_cali_boundary : <anonymous>: no visible binding for '<<-'
    #>      assignment to ‘boundary.env’
    #>    set_cali_boundary : <anonymous>: no visible binding for global variable
    #>      ‘boundary.env’
    #>    set_cali_boundary: no visible global function definition for
    #>      ‘gseparator’
    #>    set_cali_boundary: no visible global function definition for ‘gbutton’
    #> set_
      
       set_cali_boundary : <anonymous>: no visible global function definition
    #>      for ‘dispose’
    #>    set_cali_boundary: no visible global function definition for
    #>      ‘visible<-’
    #>    set_parameter: no visible global function definition for ‘gwindow’
    #>    set_parameter: no visible global function definition for ‘ggroup’
    #>    set_parameter: no visible binding for '<<-' assignment to ‘cb’
    #>    set_parameter: no visible global function definition for ‘gcombobox’
    #>    set_parameter: no visible binding for global variable ‘l’
    #>    set_parameter : <anonymous>: no visible binding for global variable
    #>      ‘List_parameter’
    #>    set_parameter : <anonymous>: no visible global function definition for
    #>      ‘read_nml’
    #>    set_parameter : <anonymous>: no visible binding for '<<-' assignment to
    #>      ‘gewaehlterwert’
    #>    set_parameter : <anonymous>: no visible global function definition for
    #>      ‘get_nml_value’
    #>    set_parameter : <anonymous>: no visible global function definition for
    #>      ‘svalue’
    #>    set_parameter : <anonymous>: no visible binding for global variable
    #>      ‘cb’
    #>    set_parameter : <anonymous>: no visible global function definition for
    #>      ‘svalue<-’
    #>    set_parameter : <anonymous>: no visible binding for global variable
    #>      ‘gewaehlterwert’
    #>    set_parameter : <anonymous>: no visible binding for '<<-' assignment to
    #>      ‘gewaehlt’
    #>    set_parameter: no visible global function definition for ‘gedit’
    #>    set_parameter: no visible binding for '<<-' assignment to
    #>      ‘button_set_parameter’
    #>    set_parameter: no visible global function definition for ‘gbutton’
    #>    set_parameter : <anonymous>: no visible binding for '<<-' assignment to
    #>      ‘List_parameter_temp’
    #>    set_parameter : <anonymous>: no visible binding for global variable
    #>      ‘List_parameter_temp’
    #>    set_parameter : <anonymous>: no visible binding for '<<-' assignment to
    #>      ‘List_parameter’
    #>    set_parameter : <anonymous>: no visible binding for '<<-' assignment to
    #>      ‘List_values’
    #>    set_parameter : <anonymous>: no visible binding for '<<-' assignment to
    #>      ‘label_nml_range’
    #>    set_parameter : <anonymous>: no visible binding for global variable
    #>    ‘label_nml_
      
         ‘label_nml_range’
    #>    set_parameter : <anonymous>: no visible global function definition for
    #>      ‘set_nml’
    #>    set_parameter : <anonymous>: no visible binding for global variable
    #>      ‘gewaehlt’
    #>    set_parameter : <anonymous>: no visible global function definition for
    #>      ‘write_nml’
    #>    set_parameter : <anonymous>: no visible global function definition for
    #>      ‘dispose’
    #>    show_message: no visible global function definition for ‘gwindow’
    #>    show_message: no visible global function definition for ‘ggroup’
    #>    show_message: no visible global function definition for ‘gimage’
    #>    show_message: no visible global function definition for ‘glabel’
    #>    show_message: no visible global function definition for ‘gbutton’
    #>    show_message : <anonymous>: no visible global function definition for
    #>      ‘dispose’
    #>    show_write_dialog: no visible global function definition for ‘gwindow’
    #>    show_write_dialog: no visible global function definition for ‘ggroup’
    #>    show_write_dialog: no visible global function definition for ‘gimage’
    #>    show_write_dialog: no visible global function definition for ‘glabel’
    #>    show_write_dialog: no visible global function definition for
    #>      ‘addSpring’
    #>    show_write_dialog: no visible global function definition for ‘gbutton’
    #>    show_write_dialog : <anonymous>: no visible binding for global variable
    #>      ‘dir_field_temp’
    #>    show_write_dialog : <anonymous>: no visible binding for global variable
    #>      ‘dir_field_level’
    #>    show_write_dialog : <anonymous>: no visible global function definition
    #>      for ‘write.csv’
    #>    show_write_dialog : <anonymous>: no visible global function definition
    #>      for ‘dispose’
    #>    show_write_dialog : <anonymous>: no visible global function definition
    #>      for ‘galert’
    #>    window_input_csv_to_plot: no visible global function definition for
    #>      ‘read.csv’
    #>    window_input_csv_to_plot: no visible binding for '<<-' assignment to
    #>      ‘list_missing_data’
    #>    window_input_csv_to_plot: no visible global function definition for
    #>      ‘gwindow’
    #>    window_input_csv_to_plot: no visible global function definition for
    #>      ‘ggroup’
    #> window_input_csv_to_plot: no visible global funct
      
       window_input_csv_to_plot: no visible global function definition for
    #>      ‘gradio’
    #>    window_input_csv_to_plot: no visible global function definition for
    #>      ‘gbutton’
    #>    window_input_csv_to_plot : repair_input: no visible global function
    #>      definition for ‘na.kalman’
    #>    window_input_csv_to_plot : repair_input: no visible binding for global
    #>      variable ‘list_missing_data’
    #>    window_input_csv_to_plot : updatePlots_repair: no visible global
    #>      function definition for ‘dev.set’
    #>    window_input_csv_to_plot : updatePlots_repair: no visible global
    #>      function definition for ‘plot’
    #>    window_input_csv_to_plot : updatePlots_repair: no visible global
    #>      function definition for ‘na.omit’
    #>    window_input_csv_to_plot : updatePlots_repair: no visible binding for
    #>      global variable ‘list_missing_data’
    #>    window_input_csv_to_plot : updatePlots_repair: no visible global
    #>      function definition for ‘points’
    #>    window_input_csv_to_plot : updatePlots_repair: no visible global
    #>      function definition for ‘legend’
    #>    window_input_csv_to_plot: no visible global function definition for
    #>      ‘glabel’
    #>    window_input_csv_to_plot: no visible global function definition for
    #>      ‘font<-’
    #>    window_input_csv_to_plot: no visible global function definition for
    #>      ‘add’
    #>    window_input_csv_to_plot: no visible global function definition for
    #>      ‘ggraphics’
    #>    window_input_csv_to_plot: no visible global function definition for
    #>      ‘dev.cur’
    #>    window_input_csv_to_plot: no visible global function definition for
    #>      ‘addHandlerClicked’
    #>    window_input_csv_to_plot : <anonymous>: no visible global function
    #>      definition for ‘svalue’
    #>    window_input_csv_to_plot : <anonymous>: no visible binding for '<<-'
    #>      assignment to ‘list_missing_data’
    #>    window_input_csv_to_plot : <anonymous>: no visible global function
    #>      definition for ‘enabled<-’
    #>    window_input_csv_to_plot : <anonymous>: no visible global function
    #>      definition for ‘svalue<-’
    #>    window_input_csv_to_plot : updatePlots: no visible global function
    #>      definition for ‘dev.set’
    #>    window_input_csv_to_plot : updatePlots: no visible global function
    #>      definition for ‘plot’
    #> window_input_csv_to_plo
      
       window_input_csv_to_plot : updatePlots: no visible global function
    #>      definition for ‘na.omit’
    #>    window_input_csv_to_plot : updatePlots: no visible binding for global
    #>      variable ‘list_missing_data’
    #>    window_input_csv_to_plot : updatePlots: no visible global function
    #>      definition for ‘points’
    #>    window_input_csv_to_plot : check_null: no visible binding for '<<-'
    #>      assignment to ‘list_missing_data’
    #>    window_input_csv_to_plot : check_null: no visible binding for global
    #>      variable ‘list_missing_data’
    #>    window_input_csv_to_plot : check_null: no visible global function
    #>      definition for ‘gmessage’
    #>    window_input_csv_to_plot : check_null: no visible global function
    #>      definition for ‘enabled<-’
    #>    window_input_csv_to_plot : check_null: no visible binding for '<<-'
    #>      assignment to ‘list_0_data’
    #>    window_input_csv_to_plot : check_null: no visible global function
    #>      definition for ‘na.omit’
    #>    window_input_csv_to_plot : check_null: no visible binding for global
    #>      variable ‘list_0_data’
    #>    window_input_csv_to_plot: no visible global function definition for
    #>      ‘enabled<-’
    #>    window_input_csv_to_plot: no visible global function definition for
    #>      ‘visible<-’
    #>    window_input_csv_to_plot2: no visible global function definition for
    #>      ‘read.csv’
    #>    window_input_csv_to_plot2: no visible binding for global variable
    #>      ‘dir_field_temp’
    #>    window_input_csv_to_plot2: no visible binding for '<<-' assignment to
    #>      ‘list_missing_data’
    #>    window_input_csv_to_plot2 : check_null: no visible binding for '<<-'
    #>      assignment to ‘list_missing_data’
    #>    window_input_csv_to_plot2 : check_null: no visible binding for global
    #>      variable ‘list_missing_data’
    #>    window_input_csv_to_plot2 : check_null: no visible global function
    #>      definition for ‘gmessage’
    #>    window_input_csv_to_plot2 : check_null: no visible global function
    #>      definition for ‘enabled<-’
    #>    window_input_csv_to_plot2: no visible global function definition for
    #>      ‘gwindow’
    #>    window_input_csv_to_plot2: no visible global function definition for
    #>      ‘ggroup’
    #>    window_input_csv_to_plot2: no visible global function definition for
    #>    ‘grad
      
         ‘gradio’
    #>    window_input_csv_to_plot2: no visible global function definition for
    #>      ‘gbutton’
    #>    window_input_csv_to_plot2: no visible binding for global variable
    #>      ‘dir_field_level’
    #>    window_input_csv_to_plot2: no visible global function definition for
    #>      ‘glabel’
    #>    window_input_csv_to_plot2: no visible global function definition for
    #>      ‘font<-’
    #>    window_input_csv_to_plot2: no visible global function definition for
    #>      ‘add’
    #>    window_input_csv_to_plot2: no visible global function definition for
    #>      ‘ggraphics’
    #>    window_input_csv_to_plot2: no visible global function definition for
    #>      ‘dev.cur’
    #>    window_input_csv_to_plot2: no visible global function definition for
    #>      ‘addHandlerClicked’
    #>    window_input_csv_to_plot2 : <anonymous>: no visible global function
    #>      definition for ‘svalue’
    #>    window_input_csv_to_plot2 : <anonymous>: no visible binding for '<<-'
    #>      assignment to ‘list_missing_data’
    #>    window_input_csv_to_plot2 : <anonymous>: no visible global function
    #>      definition for ‘enabled<-’
    #>    window_input_csv_to_plot2 : <anonymous>: no visible global function
    #>      definition for ‘svalue<-’
    #>    window_input_csv_to_plot2 : updatePlots: no visible global function
    #>      definition for ‘dev.set’
    #>    window_input_csv_to_plot2 : updatePlots: no visible global function
    #>      definition for ‘plot’
    #>    window_input_csv_to_plot2 : updatePlots: no visible global function
    #>      definition for ‘na.omit’
    #>    window_input_csv_to_plot2: no visible global function definition for
    #>      ‘enabled<-’
    #>    window_input_csv_to_plot2: no visible global function definition for
    #>      ‘visible<-’
    #>    window_output_csv_to_plot: no visible global function definition for
    #>      ‘read.csv’
    #>    window_output_csv_to_plot: no visible global function definition for
    #>      ‘gwindow’
    #>    window_output_csv_to_plot: no visible global function definition for
    #>      ‘ggroup’
    #>    window_output_csv_to_plot: no visible global function definition for
    #>      ‘gradio’
    #>    window_output_csv_to_plot: no visible global function definition for
    #>      ‘glabel’
    #>    window_output_csv_to_plot: no visible global function definition for
    #>      ‘gcombobox’
    #> window_out
      
       window_output_csv_to_plot : <anonymous>: no visible global function
    #>      definition for ‘svalue’
    #>    window_output_csv_to_plot: no visible global function definition for
    #>      ‘gcheckbox’
    #>    window_output_csv_to_plot: no visible global function definition for
    #>      ‘font<-’
    #>    window_output_csv_to_plot: no visible global function definition for
    #>      ‘add’
    #>    window_output_csv_to_plot: no visible global function definition for
    #>      ‘ggraphics’
    #>    window_output_csv_to_plot: no visible global function definition for
    #>      ‘dev.cur’
    #>    window_output_csv_to_plot: no visible global function definition for
    #>      ‘addHandlerClicked’
    #>    window_output_csv_to_plot : <anonymous>: no visible global function
    #>      definition for ‘svalue<-’
    #>    window_output_csv_to_plot : updatePlots: no visible global function
    #>      definition for ‘dev.set’
    #>    window_output_csv_to_plot : updatePlots: no visible global function
    #>      definition for ‘plot’
    #>    window_output_csv_to_plot : updatePlots: no visible global function
    #>      definition for ‘svalue’
    #>    window_output_csv_to_plot : updatePlots: no visible global function
    #>      definition for ‘lines’
    #>    window_output_csv_to_plot : updatePlots: no visible global function
    #>      definition for ‘lowess’
    #>    window_output_csv_to_plot: no visible global function definition for
    #>      ‘visible<-’
    #>    window_plot_RMSE: no visible global function definition for ‘gwindow’
    #>    window_plot_RMSE: no visible global function definition for ‘ggraphics’
    #>    window_plot_RMSE: no visible global function definition for ‘visible<-’
    #>    window_plot_RMSE: no visible binding for global variable ‘List_values’
    #>    window_plot_RMSE: no visible binding for global variable
    #>      ‘List_parameter’
    #>    window_plot_RMSE: no visible global function definition for ‘plot’
    #>    window_plot_RMSE: no visible global function definition for ‘lines’
    #>    window_plot_RMSE: no visible global function definition for
    #>      ‘shapiro.test’
    #>    window_plot_RMSE: no visible global function definition for ‘points’
    #>    window_plot_dataframe_Level_Lake: no visible global function definition
    #>      for ‘gwindow’
    #> window_plot_dataframe_Level_Lake: no visible
      
       window_plot_dataframe_Level_Lake: no visible global function definition
    #>      for ‘ggraphics’
    #>    window_plot_dataframe_Level_Lake: no visible binding for '<<-'
    #>      assignment to ‘dir_output’
    #>    window_plot_dataframe_Level_Lake: no visible global function definition
    #>      for ‘read_nml’
    #>    window_plot_dataframe_Level_Lake: no visible binding for global
    #>      variable ‘dir_output’
    #>    window_plot_dataframe_Level_Lake: no visible global function definition
    #>      for ‘get_nml_value’
    #>    window_plot_dataframe_Level_Lake: no visible global function definition
    #>      for ‘read.csv’
    #>    window_plot_dataframe_Level_Lake: no visible global function definition
    #>      for ‘plot’
    #>    window_plot_dataframe_Level_Lake: no visible global function definition
    #>      for ‘lines’
    #>    window_plot_dataframe_Level_Lake: no visible global function definition
    #>      for ‘legend’
    #>    window_plot_dataframe_Level_Lake: no visible global function definition
    #>      for ‘strwidth’
    #>    window_plot_list_graph: no visible global function definition for
    #>      ‘gwindow’
    #>    window_plot_list_graph: no visible global function definition for
    #>      ‘ggraphics’
    #>    window_plot_list_graph: no visible global function definition for
    #>      ‘visible<-’
    #>    window_plot_list_graph: no visible global function definition for ‘par’
    #>    window_plot_list_graph: no visible global function definition for
    #>      ‘n2mfrow’
    #>    window_plot_list_graph: no visible global function definition for
    #>      ‘plot’
    #>    window_plot_list_graph: no visible global function definition for
    #>      ‘points’
    #>    window_plot_list_graph: no visible global function definition for
    #>      ‘lines’
    #>    window_plot_list_temp: no visible global function definition for
    #>      ‘gwindow’
    #>    window_plot_list_temp: no visible global function definition for
    #>      ‘ggraphics’
    #>    window_plot_list_temp: no visible global function definition for
    #>      ‘visible<-’
    #>    window_plot_list_temp: no visible global function definition for ‘par’
    #>    window_plot_list_temp: no visible global function definition for
    #>      ‘n2mfrow’
    #>    window_plot_list_temp: no visible global function definition for ‘plot’
    #>    window_plot_list_temp: no visible global function definition for
    #>      ‘points’
    #> window_p
      
       window_plot_list_temp: no visible global function definition for
    #>      ‘lines’
    #>    window_plot_model_output: no visible global function definition for
    #>      ‘sim_vars’
    #>    window_plot_model_output: no visible global function definition for
    #>      ‘gwindow’
    #>    window_plot_model_output: no visible global function definition for
    #>      ‘ggroup’
    #>    window_plot_model_output: no visible global function definition for
    #>      ‘gradio’
    #>    window_plot_model_output: no visible global function definition for
    #>      ‘glabel’
    #>    window_plot_model_output: no visible global function definition for
    #>      ‘font<-’
    #>    window_plot_model_output: no visible global function definition for
    #>      ‘add’
    #>    window_plot_model_output: no visible global function definition for
    #>      ‘ggraphics’
    #>    window_plot_model_output: no visible global function definition for
    #>      ‘dev.cur’
    #>    window_plot_model_output: no visible global function definition for
    #>      ‘addHandlerClicked’
    #>    window_plot_model_output : <anonymous>: no visible global function
    #>      definition for ‘svalue’
    #>    window_plot_model_output : <anonymous>: no visible global function
    #>      definition for ‘svalue<-’
    #>    window_plot_model_output : updatePlots: no visible global function
    #>      definition for ‘dev.set’
    #>    window_plot_model_output : updatePlots: no visible global function
    #>      definition for ‘plot_var’
    #>    window_plot_model_output: no visible global function definition for
    #>      ‘visible<-’
    #>    window_plot_multi_histo: no visible global function definition for
    #>      ‘gwindow’
    #>    window_plot_multi_histo: no visible global function definition for
    #>      ‘ggraphics’
    #>    window_plot_multi_histo: no visible global function definition for
    #>      ‘par’
    #>    window_plot_multi_histo: no visible global function definition for
    #>      ‘shapiro.test’
    #>    window_plot_multi_histo: no visible global function definition for
    #>      ‘hist’
    #>    window_plot_multi_histo: no visible binding for global variable
    #>      ‘List_values’
    #>    window_plot_temp_compare: no visible global function definition for
    #>      ‘gwindow’
    #>    window_plot_temp_compare: no visible global function definition for
    #>      ‘ggraphics’
    #> window_plot_temp_compare: no vis
      
       window_plot_temp_compare: no visible global function definition for
    #>      ‘dev.cur’
    #>    window_plot_temp_compare: no visible global function definition for
    #>      ‘par’
    #>    window_plot_temp_compare: no visible global function definition for
    #>      ‘get_var’
    #>    window_plot_temp_compare: no visible global function definition for
    #>      ‘get.offsets’
    #>    window_plot_temp_compare: no visible global function definition for
    #>      ‘resample_to_field’
    #>    window_plot_temp_compare: no visible global function definition for
    #>      ‘resample_sim’
    #>    window_plot_temp_compare: no visible global function definition for
    #>      ‘interp’
    #>    window_plot_temp_compare : gen_default_fig: no visible global function
    #>      definition for ‘valid_fig_path’
    #>    window_plot_temp_compare : gen_default_fig: no visible global function
    #>      definition for ‘png’
    #>    window_plot_temp_compare : gen_default_fig: no visible global function
    #>      definition for ‘par’
    #>    window_plot_temp_compare : .stacked_layout: no visible global function
    #>      definition for ‘.simple_layout’
    #>    window_plot_temp_compare : colbar_layout: no visible global function
    #>      definition for ‘layout’
    #>    window_plot_temp_compare : .plot_df_heatmap: no visible global function
    #>      definition for ‘colorRampPalette’
    #>    window_plot_temp_compare : .plot_df_heatmap: no visible global function
    #>      definition for ‘head’
    #>    window_plot_temp_compare : .plot_df_heatmap: no visible global function
    #>      definition for ‘.filled.contour’
    #>    window_plot_temp_compare : .plot_df_heatmap_diff: no visible global
    #>      function definition for ‘colorRampPalette’
    #>    window_plot_temp_compare : .plot_df_heatmap_diff: no visible global
    #>      function definition for ‘head’
    #>    window_plot_temp_compare : .plot_df_heatmap_diff: no visible global
    #>      function definition for ‘.filled.contour’
    #>    window_plot_temp_compare : plot_layout: no visible global function
    #>      definition for ‘plot’
    #>    window_plot_temp_compare : axis_layout: no visible global function
    #>      definition for ‘axis’
    #>    window_plot_temp_compare : axis_layout: no visible global function
    #>      definition for ‘par’
    #> window_plot_temp_compare : color_key: no visible global 
      
       window_plot_temp_compare : color_key: no visible global function
    #>      definition for ‘plot’
    #>    window_plot_temp_compare : color_key: no visible global function
    #>      definition for ‘par’
    #>    window_plot_temp_compare : color_key: no visible global function
    #>      definition for ‘axis’
    #>    window_plot_temp_compare : color_key: no visible global function
    #>      definition for ‘polygon’
    #>    window_plot_temp_compare : color_key: no visible global function
    #>      definition for ‘text’
    #>    window_plot_temp_compare : color_key_diff: no visible global function
    #>      definition for ‘plot’
    #>    window_plot_temp_compare : color_key_diff: no visible global function
    #>      definition for ‘par’
    #>    window_plot_temp_compare : color_key_diff: no visible global function
    #>      definition for ‘axis’
    #>    window_plot_temp_compare : color_key_diff: no visible global function
    #>      definition for ‘polygon’
    #>    window_plot_temp_compare : color_key_diff: no visible global function
    #>      definition for ‘text’
    #>    window_plot_temp_compare: no visible global function definition for
    #>      ‘compare_to_field’
    #>    window_plot_temp_compare: no visible global function definition for
    #>      ‘dev.copy’
    #>    window_plot_temp_compare: no visible binding for global variable ‘pdf’
    #>    window_plot_temp_compare: no visible global function definition for
    #>      ‘dev.off’
    #>    window_plot_temp_compare: no visible global function definition for
    #>      ‘points’
    #>    window_plot_temp_compare: no visible global function definition for
    #>      ‘text’
    #>    window_select_SI_calculation: no visible global function definition for
    #>      ‘gwindow’
    #>    window_select_SI_calculation: no visible global function definition for
    #>      ‘ggroup’
    #>    window_select_SI_calculation: no visible global function definition for
    #>      ‘glabel’
    #>    window_select_SI_calculation: no visible global function definition for
    #>      ‘font<-’
    #>    window_select_SI_calculation: no visible global function definition for
    #>      ‘gcheckbox’
    #>    window_select_SI_calculation: no visible global function definition for
    #>      ‘gseparator’
    #>    window_select_SI_calculation: no visible global function definition for
    #>      ‘gradio’
    #> window_select_SI_calculation: no visible global function definition for
      
       window_select_SI_calculation: no visible global function definition for
    #>      ‘gbutton’
    #>    window_select_SI_calculation : <anonymous>: no visible binding for
    #>      global variable ‘dir_field_temp’
    #>    window_select_SI_calculation : <anonymous>: no visible global function
    #>      definition for ‘svalue’
    #>    window_select_SI_calculation : <anonymous>: no visible binding for
    #>      global variable ‘dir_field_level’
    #>    window_select_SI_calculation : <anonymous>: no visible global function
    #>      definition for ‘enabled<-’
    #>    window_select_SI_calculation : <anonymous>: no visible global function
    #>      definition for ‘svalue<-’
    #>    window_select_SI_calculation : <anonymous>: no visible binding for
    #>      global variable ‘label_status_SI_calculation’
    #>    window_select_SI_calculation : <anonymous>: no visible global function
    #>      definition for ‘dispose’
    #>    window_select_SI_calculation: no visible binding for '<<-' assignment
    #>      to ‘label_status_SI_calculation’
    #>    window_select_SI_calculation: no visible global function definition for
    #>      ‘visible<-’
    #>    window_select_auto_kalib: no visible global function definition for
    #>      ‘gwindow’
    #>    window_select_auto_kalib: no visible global function definition for
    #>      ‘ggroup’
    #>    window_select_auto_kalib: no visible global function definition for
    #>      ‘glabel’
    #>    window_select_auto_kalib: no visible global function definition for
    #>      ‘font<-’
    #>    window_select_auto_kalib: no visible global function definition for
    #>      ‘gcheckbox’
    #>    window_select_auto_kalib: no visible global function definition for
    #>      ‘gseparator’
    #>    window_select_auto_kalib: no visible global function definition for
    #>      ‘gradio’
    #>    window_select_auto_kalib: no visible global function definition for
    #>      ‘gslider’
    #>    window_select_auto_kalib: no visible global function definition for
    #>      ‘svalue’
    #>    window_select_auto_kalib: no visible global function definition for
    #>      ‘svalue<-’
    #>    window_select_auto_kalib: no visible global function definition for
    #>      ‘gbutton’
    #>    window_select_auto_kalib : <anonymous>: no visible binding for global
    #>      variable ‘boundary.env’
    #>    window_select_auto_kalib: no visible binding for '<<-' assignment to
    #>      ‘but_cal_si_auto’
    #> window_select_au
      
       window_select_auto_kalib : <anonymous>: no visible binding for global
    #>      variable ‘dir_field_temp’
    #>    window_select_auto_kalib : <anonymous>: no visible global function
    #>      definition for ‘svalue’
    #>    window_select_auto_kalib : <anonymous>: no visible binding for global
    #>      variable ‘dir_field_level’
    #>    window_select_auto_kalib : <anonymous>: no visible global function
    #>      definition for ‘enabled<-’
    #>    window_select_auto_kalib : <anonymous>: no visible global function
    #>      definition for ‘svalue<-’
    #>    window_select_auto_kalib : <anonymous>: no visible binding for global
    #>      variable ‘label_status_CAL_calculation’
    #>    window_select_auto_kalib : <anonymous>: no visible global function
    #>      definition for ‘dispose’
    #>    window_select_auto_kalib: no visible binding for '<<-' assignment to
    #>      ‘label_status_CAL_calculation’
    #>    window_select_auto_kalib: no visible global function definition for
    #>      ‘visible<-’
    #>    windows_main_menu: no visible global function definition for ‘gwindow’
    #>    windows_main_menu: no visible global function definition for ‘ggroup’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘workspace’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘arg_meteo’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘multi_inflow’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘multi_outflow’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘arg_inflow’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘arg_outflow’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘dir_field_temp’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘dir_field_level’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘List_parameter’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘List_values’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘dfList_Temp’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘dfList_Level’
    #> windows_main_menu: no visible global function definition fo
      
       windows_main_menu: no visible global function definition for ‘glabel’
    #>    windows_main_menu: no visible global function definition for ‘font<-’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘label_workspace’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘label_workspace_project’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘button_new_workspace’
    #>    windows_main_menu: no visible global function definition for ‘gbutton’
    #>    windows_main_menu : <anonymous>: no visible global function definition
    #>      for ‘tk_choose.dir’
    #>    windows_main_menu : <anonymous>: no visible global function definition
    #>      for ‘svalue<-’
    #>    windows_main_menu : <anonymous>: no visible binding for '<<-'
    #>      assignment to ‘workspace’
    #>    windows_main_menu : <anonymous>: no visible global function definition
    #>      for ‘read_nml’
    #>    windows_main_menu : <anonymous>: no visible global function definition
    #>      for ‘write_nml’
    #>    windows_main_menu : <anonymous>: no visible binding for global variable
    #>      ‘workspace’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘button_workspace’
    #>    windows_main_menu : <anonymous>: no visible global function definition
    #>      for ‘gwindow’
    #>    windows_main_menu : <anonymous>: no visible global function definition
    #>      for ‘ggroup’
    #>    windows_main_menu : <anonymous>: no visible global function definition
    #>      for ‘gimage’
    #>    windows_main_menu : <anonymous>: no visible global function definition
    #>      for ‘glabel’
    #>    windows_main_menu : <anonymous>: no visible global function definition
    #>      for ‘gbutton’
    #>    windows_main_menu : <anonymous> : <anonymous>: no visible global
    #>      function definition for ‘read_nml’
    #>    windows_main_menu : <anonymous> : <anonymous>: no visible global
    #>      function definition for ‘write_nml’
    #>    windows_main_menu : <anonymous> : <anonymous>: no visible binding for
    #>      global variable ‘workspace’
    #>    windows_main_menu : <anonymous> : <anonymous>: no visible global
    #>      function definition for ‘dispose’
    #>    windows_main_menu: no visible global function definition for
    #>      ‘gseparator’
    #> windows_main_menu: no visible binding for '<<-' assignment
      
       windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘label_met_data’
    #>    windows_main_menu : <anonymous>: no visible binding for global variable
    #>      ‘dir_meteo’
    #>    windows_main_menu : <anonymous>: no visible binding for global variable
    #>      ‘arg_meteo’
    #>    windows_main_menu: no visible global function definition for
    #>      ‘enabled<-’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘label_inflow_data’
    #>    windows_main_menu : <anonymous>: no visible binding for global variable
    #>      ‘multi_inflow’
    #>    windows_main_menu : <anonymous>: no visible binding for global variable
    #>      ‘dir_inflow’
    #>    windows_main_menu : <anonymous>: no visible binding for global variable
    #>      ‘arg_inflow’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘label_outflow_data’
    #>    windows_main_menu : <anonymous>: no visible binding for global variable
    #>      ‘multi_outflow’
    #>    windows_main_menu : <anonymous>: no visible binding for global variable
    #>      ‘dir_outflow’
    #>    windows_main_menu : <anonymous>: no visible binding for global variable
    #>      ‘arg_outflow’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘label_nml_status’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘label_nml_range’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘button_field_temp’
    #>    windows_main_menu : <anonymous>: no visible global function definition
    #>      for ‘tk_choose.files’
    #>    windows_main_menu : <anonymous>: no visible binding for '<<-'
    #>      assignment to ‘dir_field_temp’
    #>    windows_main_menu : <anonymous>: no visible binding for global variable
    #>      ‘dir_field_temp’
    #>    windows_main_menu : <anonymous>: no visible global function definition
    #>      for ‘enabled<-’
    #>    windows_main_menu: no visible binding for global variable
    #>      ‘button_field_temp’
    #>    windows_main_menu: no visible global function definition for
    #>      ‘gcheckbox’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘label_field_level’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘button_field_level’
    #>    windows_main_menu : <anonymous>: no visible binding for '<<-'
    #>    assignment to ‘dir_field_
      
         assignment to ‘dir_field_level’
    #>    windows_main_menu : <anonymous>: no visible binding for global variable
    #>      ‘dir_field_level’
    #>    windows_main_menu: no visible binding for global variable
    #>      ‘button_field_level’
    #>    windows_main_menu: no visible binding for '<<-' assignment to
    #>      ‘label_status_build’
    #>    windows_main_menu : <anonymous>: no visible global function definition
    #>      for ‘svalue’
    #>    windows_main_menu : <anonymous>: no visible global function definition
    #>      for ‘get_nml_value’
    #>    windows_main_menu : <anonymous>: no visible global function definition
    #>      for ‘gmessage’
    #>    windows_main_menu : <anonymous>: no visible global function definition
    #>      for ‘dispose’
    #>    windows_main_menu: no visible global function definition for
    #>      ‘visible<-’
    #>    Undefined global functions or variables:
    #>      .filled.contour .simple_layout List_parameter List_parameter_temp
    #>      List_values add addHandlerClicked addSpring aov arg_inflow arg_meteo
    #>      arg_outflow axis barplot boundary.env but_cal_si_auto
    #>      button_autocalib button_build button_cal_SI_value button_confi
    #>      button_field_level button_field_temp button_set_parameter cb
    #>      checkbox_Level_plot checkbox_Level_rmse checkbox_Temp_plot
    #>      checkbox_Temp_plot2 checkbox_Temp_plot3 checkbox_Temp_plot4
    #>      checkbox_Temp_rmse colorRampPalette compare_to_field dev.copy dev.cur
    #>      dev.off dev.set dir_field_level dir_field_temp dir_inflow dir_meteo
    #>      dir_outflow dir_output dispose enabled<- font<- galert gbutton
    #>      gcheckbox gcombobox gedit get.offsets get_nml_value get_var gewaehlt
    #>      gewaehlterwert gframe ggraphics ggroup gimage glabel gmessage gradio
    #>      gseparator gslider gwindow head hist install.packages interp k l
    #>      label_inflow_data label_met_data label_nml_range label_outflow_data
    #>      label_status_CAL_calculation label_status_SI_calculation
    #>      label_status_build layout legend lines list_0_data list_missing_data
    #>      lowess multi_inflow multi_outflow n2mfrow na.kalman na.omit par pdf
    #>      plot plot_var png points polygon read.csv read_nml resample_sim
    #>      resample_to_field run_glm set_nml shapiro.test sim_vars stack
    #>    s
      
         strwidth svalue svalue<- text tk_choose.dir tk_choose.files
    #>      valid_fig_path visible<- workspace write.csv write.table write_nml
    #>    Consider adding
    #>      importFrom("grDevices", "colorRampPalette", "dev.copy", "dev.cur",
    #>                 "dev.off", "dev.set", "n2mfrow", "pdf", "png")
    #>      importFrom("graphics", ".filled.contour", "axis", "barplot", "hist",
    #>                 "layout", "legend", "lines", "par", "plot", "points",
    #>                 "polygon", "strwidth", "text")
    #>      importFrom("stats", "aov", "lowess", "na.omit", "shapiro.test")
    #>      importFrom("utils", "head", "install.packages", "read.csv", "stack",
    #>                 "write.csv", "write.table")
    #>    to your NAMESPACE file.
    #>    checking for missing documentation entries ...
      
    W  checking for missing documentation entries
    #>    Undocumented code objects:
    #>      ‘build_model’ ‘calculate_RMSE’ ‘calculate_SI_value’ ‘calculate_aov’
    #>      ‘calculate_auto_kalib’ ‘calculate_diff_modell_field’
    #>      ‘calculate_needed_time’ ‘calculate_needed_time2’
    #>      ‘calculate_rel_SI_LL’ ‘calculate_rel_SI_RMSE’ ‘calculate_rel_SI_WT’
    #>      ‘check_data_connection’ ‘get_Vektor_of_all_values’
    #>      ‘get_dataframe_Level_Lake’ ‘get_parameter’
    #>      ‘get_pre_list_of_default_values’ ‘glmGUI’ ‘set_cali_boundary’
    #>      ‘set_parameter’ ‘show_message’ ‘show_write_dialog’
    #>      ‘window_input_csv_to_plot’ ‘window_input_csv_to_plot2’
    #>      ‘window_output_csv_to_plot’ ‘window_plot_RMSE’
    #>      ‘window_plot_dataframe_Level_Lake’ ‘window_plot_list_graph’
    #>      ‘window_plot_list_temp’ ‘window_plot_model_output’
    #>      ‘window_plot_multi_histo’ ‘window_plot_temp_compare’
    #>      ‘window_select_SI_calculation’ ‘window_select_auto_kalib’
    #>      ‘windows_main_menu’
    #>    Undocumented data sets:
    #>      ‘boundary.env’
    #> 
      
       All user-level objects in a package should have documentation entries.
    #>    See chapter ‘Writing R documentation files’ in the ‘Writing R
    #>    Extensions’ manual.
    #> ✔  checking contents of ‘data’ directory
    #>    checking data for non-ASCII characters ...
      
    ✔  checking data for non-ASCII characters
    #> 
      
       checking data for ASCII and uncompressed saves ...
      
    ✔  checking data for ASCII and uncompressed saves
    #> 
      
       checking examples ...
      
    ─  checking examples ... NONE
    #> 
      
       
    #>    See
    #>      ‘/tmp/Rtmp13TM60/glmgui.Rcheck/00check.log’
    #>    for details.
    #>    
    #> 
      
    
      
       
    #> 
    ── R CMD check results ──────────────────────────────────── glmgui 1.0 ────
    #> Duration: 12.7s
    #> 
    #> ❯ checking dependencies in R code ... WARNING
    #>   'library' or 'require' calls not declared from:
    #>     ‘GLMr’ ‘glmtools’
    #>   'library' or 'require' calls in package code:
    #>     ‘GLMr’ ‘glmtools’
    #>     Please use :: or requireNamespace() instead.
    #>     See section 'Suggested packages' in the 'Writing R Extensions' manual.
    #> 
    #> ❯ checking for missing documentation entries ... WARNING
    #>   Undocumented code objects:
    #>     ‘build_model’ ‘calculate_RMSE’ ‘calculate_SI_value’ ‘calculate_aov’
    #>     ‘calculate_auto_kalib’ ‘calculate_diff_modell_field’
    #>     ‘calculate_needed_time’ ‘calculate_needed_time2’
    #>     ‘calculate_rel_SI_LL’ ‘calculate_rel_SI_RMSE’ ‘calculate_rel_SI_WT’
    #>     ‘check_data_connection’ ‘get_Vektor_of_all_values’
    #>     ‘get_dataframe_Level_Lake’ ‘get_parameter’
    #>     ‘get_pre_list_of_default_values’ ‘glmGUI’ ‘set_cali_boundary’
    #>     ‘set_parameter’ ‘show_message’ ‘show_write_dialog’
    #>     ‘window_input_csv_to_plot’ ‘window_input_csv_to_plot2’
    #>     ‘window_output_csv_to_plot’ ‘window_plot_RMSE’
    #>     ‘window_plot_dataframe_Level_Lake’ ‘window_plot_list_graph’
    #>     ‘window_plot_list_temp’ ‘window_plot_model_output’
    #>     ‘window_plot_multi_histo’ ‘window_plot_temp_compare’
    #>     ‘window_select_SI_calculation’ ‘window_select_auto_kalib’
    #>     ‘windows_main_menu’
    #>   Undocumented data sets:
    #>     ‘boundary.env’
    #>   All user-level objects in a package should have documentation entries.
    #>   See chapter ‘Writing R documentation files’ in the ‘Writing R
    #>   Extensions’ manual.
    #> 
    #> ❯ checking R code for possible problems ... NOTE
    #>   build_model: no visible binding for '<<-' assignment to
    #>     ‘label_status_build’
    #>   build_model: no visible binding for global variable
    #>     ‘label_status_build’
    #>   build_model: no visible global function definition for ‘svalue<-’
    #>   build_model: no visible binding for global variable ‘List_values’
    #>   build_model: no visible global function definition for ‘svalue’
    #>   build_model: no visible binding for global variable ‘button_build’
    #>   build_model: no visible binding for '<<-' assignment to ‘dir_output’
    #>   build_model: no visible binding for global variable ‘dir_output’
    #>   build_model: no visible global function definition for ‘read_nml’
    #>   build_model: no visible global function definition for ‘get_nml_value’
    #>   build_model: no visible global function definition for ‘set_nml’
    #>   build_model: no visible binding for global variable ‘List_parameter’
    #>   build_model: no visible global function definition for ‘write_nml’
    #>   build_model: no visible global function definition for ‘run_glm’
    #>   build_model: no visible binding for global variable
    #>     ‘checkbox_Level_plot’
    #>   build_model: no visible binding for global variable
    #>     ‘checkbox_Level_rmse’
    #>   build_model: no visible binding for global variable ‘dir_field_level’
    #>   build_model: no visible binding for global variable
    #>     ‘checkbox_Temp_plot’
    #>   build_model: no visible binding for global variable
    #>     ‘checkbox_Temp_rmse’
    #>   build_model: no visible global function definition for
    #>     ‘compare_to_field’
    #>   build_model: no visible binding for global variable ‘dir_field_temp’
    #>   build_model: no visible global function definition for ‘gwindow’
    #>   build_model: no visible global function definition for ‘ggraphics’
    #>   build_model: no visible global function definition for ‘dev.cur’
    #>   build_model: no visible global function definition for ‘plot’
    #>   build_model: no visible binding for global variable
    #>     ‘checkbox_Temp_plot2’
    #>   build_model: no visible binding for global variable
    #>     ‘checkbox_Temp_plot3’
    #>   build_model: no visible binding for global variable
    #>     ‘checkbox_Temp_plot4’
    #>   build_model: no visible binding for '<<-' assignment to ‘button_build’
    #>   calculate_SI_value: no visible global function definition for ‘run_glm’
    #>   calculate_SI_value: no visible global function definition for
    #>     ‘svalue<-’
    #>   calculate_SI_value: no visible binding for '<<-' assignment to
    #>     ‘dir_output’
    #>   calculate_SI_value: no visible binding for global variable ‘dir_output’
    #>   calculate_SI_value: no visible global function definition for
    #>     ‘read_nml’
    #>   calculate_SI_value: no visible global function definition for
    #>     ‘get_nml_value’
    #>   calculate_SI_value: no visible global function definition for ‘svalue’
    #>   calculate_SI_value: no visible global function definition for ‘set_nml’
    #>   calculate_SI_value: no visible global function definition for
    #>     ‘write_nml’
    #>   calculate_SI_value: no visible global function definition for
    #>     ‘compare_to_field’
    #>   calculate_SI_value: no visible binding for global variable
    #>     ‘dir_field_temp’
    #>   calculate_SI_value: no visible binding for global variable
    #>     ‘dir_field_level’
    #>   calculate_SI_value: no visible global function definition for
    #>     ‘write.csv’
    #>   calculate_SI_value: no visible global function definition for ‘gwindow’
    #>   calculate_SI_value: no visible global function definition for
    #>     ‘ggraphics’
    #>   calculate_SI_value: no visible global function definition for ‘dev.cur’
    #>   calculate_SI_value: no visible global function definition for ‘par’
    #>   calculate_SI_value: no visible global function definition for ‘barplot’
    #>   calculate_aov: no visible global function definition for ‘stack’
    #>   calculate_aov: no visible global function definition for ‘aov’
    #>   calculate_auto_kalib: no visible global function definition for
    #>     ‘run_glm’
    #>   calculate_auto_kalib: no visible global function definition for
    #>     ‘svalue<-’
    #>   calculate_auto_kalib: no visible binding for '<<-' assignment to
    #>     ‘dir_output’
    #>   calculate_auto_kalib: no visible binding for global variable
    #>     ‘dir_output’
    #>   calculate_auto_kalib: no visible global function definition for
    #>     ‘read_nml’
    #>   calculate_auto_kalib: no visible global function definition for
    #>     ‘get_nml_value’
    #>   calculate_auto_kalib: no visible binding for global variable
    #>     ‘but_cal_si_auto’
    #>   calculate_auto_kalib: no visible global function definition for
    #>     ‘set_nml’
    #>   calculate_auto_kalib: no visible global function definition for
    #>     ‘write_nml’
    #>   calculate_auto_kalib: no visible global function definition for
    #>     ‘compare_to_field’
    #>   calculate_auto_kalib: no visible binding for global variable
    #>     ‘dir_field_temp’
    #>   calculate_auto_kalib: no visible binding for global variable
    #>     ‘dir_field_level’
    #>   calculate_auto_kalib: no visible global function definition for
    #>     ‘write.table’
    #>   calculate_needed_time: no visible global function definition for
    #>     ‘svalue<-’
    #>   calculate_needed_time2: no visible global function definition for
    #>     ‘svalue<-’
    #>   check_data_connection: no visible global function definition for
    #>     ‘read_nml’
    #>   check_data_connection: no visible global function definition for
    #>     ‘svalue<-’
    #>   check_data_connection: no visible global function definition for
    #>     ‘get_nml_value’
    #>   check_data_connection: no visible binding for '<<-' assignment to
    #>     ‘button_confi’
    #>   check_data_connection: no visible binding for global variable
    #>     ‘button_confi’
    #>   check_data_connection: no visible global function definition for
    #>     ‘enabled<-’
    #>   check_data_connection: no visible binding for '<<-' assignment to
    #>     ‘button_set_parameter’
    #>   check_data_connection: no visible binding for global variable
    #>     ‘button_set_parameter’
    #>   check_data_connection: no visible binding for '<<-' assignment to
    #>     ‘button_build’
    #>   check_data_connection: no visible binding for global variable
    #>     ‘button_build’
    #>   check_data_connection: no visible binding for '<<-' assignment to
    #>     ‘button_cal_SI_value’
    #>   check_data_connection: no visible binding for global variable
    #>     ‘button_cal_SI_value’
    #>   check_data_connection: no visible binding for '<<-' assignment to
    #>     ‘button_field_level’
    #>   check_data_connection: no visible binding for global variable
    #>     ‘button_field_level’
    #>   check_data_connection: no visible binding for '<<-' assignment to
    #>     ‘button_field_temp’
    #>   check_data_connection: no visible binding for global variable
    #>     ‘button_field_temp’
    #>   check_data_connection: no visible binding for '<<-' assignment to
    #>     ‘button_autocalib’
    #>   check_data_connection: no visible binding for global variable
    #>     ‘button_autocalib’
    #>   check_data_connection: no visible binding for '<<-' assignment to ‘l’
    #>   check_data_connection: no visible binding for '<<-' assignment to ‘k’
    #>   check_data_connection: no visible binding for global variable ‘l’
    #>   check_data_connection: no visible binding for global variable ‘k’
    #>   check_data_connection: no visible binding for '<<-' assignment to
    #>     ‘dir_meteo’
    #>   check_data_connection: no visible binding for '<<-' assignment to
    #>     ‘arg_meteo’
    #>   check_data_connection: no visible binding for global variable
    #>     ‘dir_meteo’
    #>   check_data_connection: no visible binding for '<<-' assignment to
    #>     ‘label_met_data’
    #>   check_data_connection: no visible binding for global variable
    #>     ‘label_met_data’
    #>   check_data_connection: no visible binding for '<<-' assignment to
    #>     ‘multi_inflow’
    #>   check_data_connection: no visible binding for global variable
    #>     ‘multi_inflow’
    #>   check_data_connection: no visible binding for '<<-' assignment to
    #>     ‘label_inflow_data’
    #>   check_data_connection: no visible binding for global variable
    #>     ‘label_inflow_data’
    #>   check_data_connection: no visible binding for '<<-' assignment to
    #>     ‘arg_inflow’
    #>   check_data_connection: no visible binding for '<<-' assignment to
    #>     ‘dir_inflow’
    #>   check_data_connection: no visible binding for global variable
    #>     ‘dir_inflow’
    #>   check_data_connection: no visible binding for '<<-' assignment to
    #>     ‘multi_outflow’
    #>   check_data_connection: no visible binding for global variable
    #>     ‘multi_outflow’
    #>   check_data_connection: no visible binding for '<<-' assignment to
    #>     ‘label_outflow_data’
    #>   check_data_connection: no visible binding for global variable
    #>     ‘label_outflow_data’
    #>   check_data_connection: no visible binding for '<<-' assignment to
    #>     ‘dir_outflow’
    #>   check_data_connection: no visible binding for global variable
    #>     ‘dir_outflow’
    #>   get_dataframe_Level_Lake: no visible global function definition for
    #>     ‘read.csv’
    #>   get_dataframe_Level_Lake: no visible global function definition for
    #>     ‘na.omit’
    #>   get_parameter: no visible global function definition for ‘read_nml’
    #>   get_parameter: no visible global function definition for ‘gwindow’
    #>   get_parameter: no visible global function definition for ‘ggroup’
    #>   get_parameter: no visible global function definition for ‘glabel’
    #>   get_parameter: no visible global function definition for ‘font<-’
    #>   get_parameter: no visible global function definition for
    #>     ‘get_nml_value’
    #>   get_parameter: no visible global function definition for ‘gedit’
    #>   get_parameter: no visible global function definition for ‘gseparator’
    #>   get_parameter: no visible global function definition for ‘visible<-’
    #>   get_pre_list_of_default_values: no visible binding for global variable
    #>     ‘workspace’
    #>   get_pre_list_of_default_values: no visible global function definition
    #>     for ‘read_nml’
    #>   get_pre_list_of_default_values: no visible global function definition
    #>     for ‘svalue’
    #>   get_pre_list_of_default_values: no visible global function definition
    #>     for ‘svalue<-’
    #>   get_pre_list_of_default_values: no visible global function definition
    #>     for ‘get_nml_value’
    #>   glmGUI: no visible global function definition for ‘install.packages’
    #>   set_cali_boundary: no visible global function definition for ‘gwindow’
    #>   set_cali_boundary: no visible global function definition for ‘gframe’
    #>   set_cali_boundary: no visible global function definition for ‘ggroup’
    #>   set_cali_boundary: no visible global function definition for ‘glabel’
    #>   set_cali_boundary: no visible global function definition for
    #>     ‘gcombobox’
    #>   set_cali_boundary : <anonymous>: no visible global function definition
    #>     for ‘svalue’
    #>   set_cali_boundary : <anonymous>: no visible binding for '<<-'
    #>     assignment to ‘boundary.env’
    #>   set_cali_boundary : <anonymous>: no visible binding for global variable
    #>     ‘boundary.env’
    #>   set_cali_boundary: no visible global function definition for
    #>     ‘gseparator’
    #>   set_cali_boundary: no visible global function definition for ‘gbutton’
    #>   set_cali_boundary : <anonymous>: no visible global function definition
    #>     for ‘dispose’
    #>   set_cali_boundary: no visible global function definition for
    #>     ‘visible<-’
    #>   set_parameter: no visible global function definition for ‘gwindow’
    #>   set_parameter: no visible global function definition for ‘ggroup’
    #>   set_parameter: no visible binding for '<<-' assignment to ‘cb’
    #>   set_parameter: no visible global function definition for ‘gcombobox’
    #>   set_parameter: no visible binding for global variable ‘l’
    #>   set_parameter : <anonymous>: no visible binding for global variable
    #>     ‘List_parameter’
    #>   set_parameter : <anonymous>: no visible global function definition for
    #>     ‘read_nml’
    #>   set_parameter : <anonymous>: no visible binding for '<<-' assignment to
    #>     ‘gewaehlterwert’
    #>   set_parameter : <anonymous>: no visible global function definition for
    #>     ‘get_nml_value’
    #>   set_parameter : <anonymous>: no visible global function definition for
    #>     ‘svalue’
    #>   set_parameter : <anonymous>: no visible binding for global variable
    #>     ‘cb’
    #>   set_parameter : <anonymous>: no visible global function definition for
    #>     ‘svalue<-’
    #>   set_parameter : <anonymous>: no visible binding for global variable
    #>     ‘gewaehlterwert’
    #>   set_parameter : <anonymous>: no visible binding for '<<-' assignment to
    #>     ‘gewaehlt’
    #>   set_parameter: no visible global function definition for ‘gedit’
    #>   set_parameter: no visible binding for '<<-' assignment to
    #>     ‘button_set_parameter’
    #>   set_parameter: no visible global function definition for ‘gbutton’
    #>   set_parameter : <anonymous>: no visible binding for '<<-' assignment to
    #>     ‘List_parameter_temp’
    #>   set_parameter : <anonymous>: no visible binding for global variable
    #>     ‘List_parameter_temp’
    #>   set_parameter : <anonymous>: no visible binding for '<<-' assignment to
    #>     ‘List_parameter’
    #>   set_parameter : <anonymous>: no visible binding for '<<-' assignment to
    #>     ‘List_values’
    #>   set_parameter : <anonymous>: no visible binding for '<<-' assignment to
    #>     ‘label_nml_range’
    #>   set_parameter : <anonymous>: no visible binding for global variable
    #>     ‘label_nml_range’
    #>   set_parameter : <anonymous>: no visible global function definition for
    #>     ‘set_nml’
    #>   set_parameter : <anonymous>: no visible binding for global variable
    #>     ‘gewaehlt’
    #>   set_parameter : <anonymous>: no visible global function definition for
    #>     ‘write_nml’
    #>   set_parameter : <anonymous>: no visible global function definition for
    #>     ‘dispose’
    #>   show_message: no visible global function definition for ‘gwindow’
    #>   show_message: no visible global function definition for ‘ggroup’
    #>   show_message: no visible global function definition for ‘gimage’
    #>   show_message: no visible global function definition for ‘glabel’
    #>   show_message: no visible global function definition for ‘gbutton’
    #>   show_message : <anonymous>: no visible global function definition for
    #>     ‘dispose’
    #>   show_write_dialog: no visible global function definition for ‘gwindow’
    #>   show_write_dialog: no visible global function definition for ‘ggroup’
    #>   show_write_dialog: no visible global function definition for ‘gimage’
    #>   show_write_dialog: no visible global function definition for ‘glabel’
    #>   show_write_dialog: no visible global function definition for
    #>     ‘addSpring’
    #>   show_write_dialog: no visible global function definition for ‘gbutton’
    #>   show_write_dialog : <anonymous>: no visible binding for global variable
    #>     ‘dir_field_temp’
    #>   show_write_dialog : <anonymous>: no visible binding for global variable
    #>     ‘dir_field_level’
    #>   show_write_dialog : <anonymous>: no visible global function definition
    #>     for ‘write.csv’
    #>   show_write_dialog : <anonymous>: no visible global function definition
    #>     for ‘dispose’
    #>   show_write_dialog : <anonymous>: no visible global function definition
    #>     for ‘galert’
    #>   window_input_csv_to_plot: no visible global function definition for
    #>     ‘read.csv’
    #>   window_input_csv_to_plot: no visible binding for '<<-' assignment to
    #>     ‘list_missing_data’
    #>   window_input_csv_to_plot: no visible global function definition for
    #>     ‘gwindow’
    #>   window_input_csv_to_plot: no visible global function definition for
    #>     ‘ggroup’
    #>   window_input_csv_to_plot: no visible global function definition for
    #>     ‘gradio’
    #>   window_input_csv_to_plot: no visible global function definition for
    #>     ‘gbutton’
    #>   window_input_csv_to_plot : repair_input: no visible global function
    #>     definition for ‘na.kalman’
    #>   window_input_csv_to_plot : repair_input: no visible binding for global
    #>     variable ‘list_missing_data’
    #>   window_input_csv_to_plot : updatePlots_repair: no visible global
    #>     function definition for ‘dev.set’
    #>   window_input_csv_to_plot : updatePlots_repair: no visible global
    #>     function definition for ‘plot’
    #>   window_input_csv_to_plot : updatePlots_repair: no visible global
    #>     function definition for ‘na.omit’
    #>   window_input_csv_to_plot : updatePlots_repair: no visible binding for
    #>     global variable ‘list_missing_data’
    #>   window_input_csv_to_plot : updatePlots_repair: no visible global
    #>     function definition for ‘points’
    #>   window_input_csv_to_plot : updatePlots_repair: no visible global
    #>     function definition for ‘legend’
    #>   window_input_csv_to_plot: no visible global function definition for
    #>     ‘glabel’
    #>   window_input_csv_to_plot: no visible global function definition for
    #>     ‘font<-’
    #>   window_input_csv_to_plot: no visible global function definition for
    #>     ‘add’
    #>   window_input_csv_to_plot: no visible global function definition for
    #>     ‘ggraphics’
    #>   window_input_csv_to_plot: no visible global function definition for
    #>     ‘dev.cur’
    #>   window_input_csv_to_plot: no visible global function definition for
    #>     ‘addHandlerClicked’
    #>   window_input_csv_to_plot : <anonymous>: no visible global function
    #>     definition for ‘svalue’
    #>   window_input_csv_to_plot : <anonymous>: no visible binding for '<<-'
    #>     assignment to ‘list_missing_data’
    #>   window_input_csv_to_plot : <anonymous>: no visible global function
    #>     definition for ‘enabled<-’
    #>   window_input_csv_to_plot : <anonymous>: no visible global function
    #>     definition for ‘svalue<-’
    #>   window_input_csv_to_plot : updatePlots: no visible global function
    #>     definition for ‘dev.set’
    #>   window_input_csv_to_plot : updatePlots: no visible global function
    #>     definition for ‘plot’
    #>   window_input_csv_to_plot : updatePlots: no visible global function
    #>     definition for ‘na.omit’
    #>   window_input_csv_to_plot : updatePlots: no visible binding for global
    #>     variable ‘list_missing_data’
    #>   window_input_csv_to_plot : updatePlots: no visible global function
    #>     definition for ‘points’
    #>   window_input_csv_to_plot : check_null: no visible binding for '<<-'
    #>     assignment to ‘list_missing_data’
    #>   window_input_csv_to_plot : check_null: no visible binding for global
    #>     variable ‘list_missing_data’
    #>   window_input_csv_to_plot : check_null: no visible global function
    #>     definition for ‘gmessage’
    #>   window_input_csv_to_plot : check_null: no visible global function
    #>     definition for ‘enabled<-’
    #>   window_input_csv_to_plot : check_null: no visible binding for '<<-'
    #>     assignment to ‘list_0_data’
    #>   window_input_csv_to_plot : check_null: no visible global function
    #>     definition for ‘na.omit’
    #>   window_input_csv_to_plot : check_null: no visible binding for global
    #>     variable ‘list_0_data’
    #>   window_input_csv_to_plot: no visible global function definition for
    #>     ‘enabled<-’
    #>   window_input_csv_to_plot: no visible global function definition for
    #>     ‘visible<-’
    #>   window_input_csv_to_plot2: no visible global function definition for
    #>     ‘read.csv’
    #>   window_input_csv_to_plot2: no visible binding for global variable
    #>     ‘dir_field_temp’
    #>   window_input_csv_to_plot2: no visible binding for '<<-' assignment to
    #>     ‘list_missing_data’
    #>   window_input_csv_to_plot2 : check_null: no visible binding for '<<-'
    #>     assignment to ‘list_missing_data’
    #>   window_input_csv_to_plot2 : check_null: no visible binding for global
    #>     variable ‘list_missing_data’
    #>   window_input_csv_to_plot2 : check_null: no visible global function
    #>     definition for ‘gmessage’
    #>   window_input_csv_to_plot2 : check_null: no visible global function
    #>     definition for ‘enabled<-’
    #>   window_input_csv_to_plot2: no visible global function definition for
    #>     ‘gwindow’
    #>   window_input_csv_to_plot2: no visible global function definition for
    #>     ‘ggroup’
    #>   window_input_csv_to_plot2: no visible global function definition for
    #>     ‘gradio’
    #>   window_input_csv_to_plot2: no visible global function definition for
    #>     ‘gbutton’
    #>   window_input_csv_to_plot2: no visible binding for global variable
    #>     ‘dir_field_level’
    #>   window_input_csv_to_plot2: no visible global function definition for
    #>     ‘glabel’
    #>   window_input_csv_to_plot2: no visible global function definition for
    #>     ‘font<-’
    #>   window_input_csv_to_plot2: no visible global function definition for
    #>     ‘add’
    #>   window_input_csv_to_plot2: no visible global function definition for
    #>     ‘ggraphics’
    #>   window_input_csv_to_plot2: no visible global function definition for
    #>     ‘dev.cur’
    #>   window_input_csv_to_plot2: no visible global function definition for
    #>     ‘addHandlerClicked’
    #>   window_input_csv_to_plot2 : <anonymous>: no visible global function
    #>     definition for ‘svalue’
    #>   window_input_csv_to_plot2 : <anonymous>: no visible binding for '<<-'
    #>     assignment to ‘list_missing_data’
    #>   window_input_csv_to_plot2 : <anonymous>: no visible global function
    #>     definition for ‘enabled<-’
    #>   window_input_csv_to_plot2 : <anonymous>: no visible global function
    #>     definition for ‘svalue<-’
    #>   window_input_csv_to_plot2 : updatePlots: no visible global function
    #>     definition for ‘dev.set’
    #>   window_input_csv_to_plot2 : updatePlots: no visible global function
    #>     definition for ‘plot’
    #>   window_input_csv_to_plot2 : updatePlots: no visible global function
    #>     definition for ‘na.omit’
    #>   window_input_csv_to_plot2: no visible global function definition for
    #>     ‘enabled<-’
    #>   window_input_csv_to_plot2: no visible global function definition for
    #>     ‘visible<-’
    #>   window_output_csv_to_plot: no visible global function definition for
    #>     ‘read.csv’
    #>   window_output_csv_to_plot: no visible global function definition for
    #>     ‘gwindow’
    #>   window_output_csv_to_plot: no visible global function definition for
    #>     ‘ggroup’
    #>   window_output_csv_to_plot: no visible global function definition for
    #>     ‘gradio’
    #>   window_output_csv_to_plot: no visible global function definition for
    #>     ‘glabel’
    #>   window_output_csv_to_plot: no visible global function definition for
    #>     ‘gcombobox’
    #>   window_output_csv_to_plot : <anonymous>: no visible global function
    #>     definition for ‘svalue’
    #>   window_output_csv_to_plot: no visible global function definition for
    #>     ‘gcheckbox’
    #>   window_output_csv_to_plot: no visible global function definition for
    #>     ‘font<-’
    #>   window_output_csv_to_plot: no visible global function definition for
    #>     ‘add’
    #>   window_output_csv_to_plot: no visible global function definition for
    #>     ‘ggraphics’
    #>   window_output_csv_to_plot: no visible global function definition for
    #>     ‘dev.cur’
    #>   window_output_csv_to_plot: no visible global function definition for
    #>     ‘addHandlerClicked’
    #>   window_output_csv_to_plot : <anonymous>: no visible global function
    #>     definition for ‘svalue<-’
    #>   window_output_csv_to_plot : updatePlots: no visible global function
    #>     definition for ‘dev.set’
    #>   window_output_csv_to_plot : updatePlots: no visible global function
    #>     definition for ‘plot’
    #>   window_output_csv_to_plot : updatePlots: no visible global function
    #>     definition for ‘svalue’
    #>   window_output_csv_to_plot : updatePlots: no visible global function
    #>     definition for ‘lines’
    #>   window_output_csv_to_plot : updatePlots: no visible global function
    #>     definition for ‘lowess’
    #>   window_output_csv_to_plot: no visible global function definition for
    #>     ‘visible<-’
    #>   window_plot_RMSE: no visible global function definition for ‘gwindow’
    #>   window_plot_RMSE: no visible global function definition for ‘ggraphics’
    #>   window_plot_RMSE: no visible global function definition for ‘visible<-’
    #>   window_plot_RMSE: no visible binding for global variable ‘List_values’
    #>   window_plot_RMSE: no visible binding for global variable
    #>     ‘List_parameter’
    #>   window_plot_RMSE: no visible global function definition for ‘plot’
    #>   window_plot_RMSE: no visible global function definition for ‘lines’
    #>   window_plot_RMSE: no visible global function definition for
    #>     ‘shapiro.test’
    #>   window_plot_RMSE: no visible global function definition for ‘points’
    #>   window_plot_dataframe_Level_Lake: no visible global function definition
    #>     for ‘gwindow’
    #>   window_plot_dataframe_Level_Lake: no visible global function definition
    #>     for ‘ggraphics’
    #>   window_plot_dataframe_Level_Lake: no visible binding for '<<-'
    #>     assignment to ‘dir_output’
    #>   window_plot_dataframe_Level_Lake: no visible global function definition
    #>     for ‘read_nml’
    #>   window_plot_dataframe_Level_Lake: no visible binding for global
    #>     variable ‘dir_output’
    #>   window_plot_dataframe_Level_Lake: no visible global function definition
    #>     for ‘get_nml_value’
    #>   window_plot_dataframe_Level_Lake: no visible global function definition
    #>     for ‘read.csv’
    #>   window_plot_dataframe_Level_Lake: no visible global function definition
    #>     for ‘plot’
    #>   window_plot_dataframe_Level_Lake: no visible global function definition
    #>     for ‘lines’
    #>   window_plot_dataframe_Level_Lake: no visible global function definition
    #>     for ‘legend’
    #>   window_plot_dataframe_Level_Lake: no visible global function definition
    #>     for ‘strwidth’
    #>   window_plot_list_graph: no visible global function definition for
    #>     ‘gwindow’
    #>   window_plot_list_graph: no visible global function definition for
    #>     ‘ggraphics’
    #>   window_plot_list_graph: no visible global function definition for
    #>     ‘visible<-’
    #>   window_plot_list_graph: no visible global function definition for ‘par’
    #>   window_plot_list_graph: no visible global function definition for
    #>     ‘n2mfrow’
    #>   window_plot_list_graph: no visible global function definition for
    #>     ‘plot’
    #>   window_plot_list_graph: no visible global function definition for
    #>     ‘points’
    #>   window_plot_list_graph: no visible global function definition for
    #>     ‘lines’
    #>   window_plot_list_temp: no visible global function definition for
    #>     ‘gwindow’
    #>   window_plot_list_temp: no visible global function definition for
    #>     ‘ggraphics’
    #>   window_plot_list_temp: no visible global function definition for
    #>     ‘visible<-’
    #>   window_plot_list_temp: no visible global function definition for ‘par’
    #>   window_plot_list_temp: no visible global function definition for
    #>     ‘n2mfrow’
    #>   window_plot_list_temp: no visible global function definition for ‘plot’
    #>   window_plot_list_temp: no visible global function definition for
    #>     ‘points’
    #>   window_plot_list_temp: no visible global function definition for
    #>     ‘lines’
    #>   window_plot_model_output: no visible global function definition for
    #>     ‘sim_vars’
    #>   window_plot_model_output: no visible global function definition for
    #>     ‘gwindow’
    #>   window_plot_model_output: no visible global function definition for
    #>     ‘ggroup’
    #>   window_plot_model_output: no visible global function definition for
    #>     ‘gradio’
    #>   window_plot_model_output: no visible global function definition for
    #>     ‘glabel’
    #>   window_plot_model_output: no visible global function definition for
    #>     ‘font<-’
    #>   window_plot_model_output: no visible global function definition for
    #>     ‘add’
    #>   window_plot_model_output: no visible global function definition for
    #>     ‘ggraphics’
    #>   window_plot_model_output: no visible global function definition for
    #>     ‘dev.cur’
    #>   window_plot_model_output: no visible global function definition for
    #>     ‘addHandlerClicked’
    #>   window_plot_model_output : <anonymous>: no visible global function
    #>     definition for ‘svalue’
    #>   window_plot_model_output : <anonymous>: no visible global function
    #>     definition for ‘svalue<-’
    #>   window_plot_model_output : updatePlots: no visible global function
    #>     definition for ‘dev.set’
    #>   window_plot_model_output : updatePlots: no visible global function
    #>     definition for ‘plot_var’
    #>   window_plot_model_output: no visible global function definition for
    #>     ‘visible<-’
    #>   window_plot_multi_histo: no visible global function definition for
    #>     ‘gwindow’
    #>   window_plot_multi_histo: no visible global function definition for
    #>     ‘ggraphics’
    #>   window_plot_multi_histo: no visible global function definition for
    #>     ‘par’
    #>   window_plot_multi_histo: no visible global function definition for
    #>     ‘shapiro.test’
    #>   window_plot_multi_histo: no visible global function definition for
    #>     ‘hist’
    #>   window_plot_multi_histo: no visible binding for global variable
    #>     ‘List_values’
    #>   window_plot_temp_compare: no visible global function definition for
    #>     ‘gwindow’
    #>   window_plot_temp_compare: no visible global function definition for
    #>     ‘ggraphics’
    #>   window_plot_temp_compare: no visible global function definition for
    #>     ‘dev.cur’
    #>   window_plot_temp_compare: no visible global function definition for
    #>     ‘par’
    #>   window_plot_temp_compare: no visible global function definition for
    #>     ‘get_var’
    #>   window_plot_temp_compare: no visible global function definition for
    #>     ‘get.offsets’
    #>   window_plot_temp_compare: no visible global function definition for
    #>     ‘resample_to_field’
    #>   window_plot_temp_compare: no visible global function definition for
    #>     ‘resample_sim’
    #>   window_plot_temp_compare: no visible global function definition for
    #>     ‘interp’
    #>   window_plot_temp_compare : gen_default_fig: no visible global function
    #>     definition for ‘valid_fig_path’
    #>   window_plot_temp_compare : gen_default_fig: no visible global function
    #>     definition for ‘png’
    #>   window_plot_temp_compare : gen_default_fig: no visible global function
    #>     definition for ‘par’
    #>   window_plot_temp_compare : .stacked_layout: no visible global function
    #>     definition for ‘.simple_layout’
    #>   window_plot_temp_compare : colbar_layout: no visible global function
    #>     definition for ‘layout’
    #>   window_plot_temp_compare : .plot_df_heatmap: no visible global function
    #>     definition for ‘colorRampPalette’
    #>   window_plot_temp_compare : .plot_df_heatmap: no visible global function
    #>     definition for ‘head’
    #>   window_plot_temp_compare : .plot_df_heatmap: no visible global function
    #>     definition for ‘.filled.contour’
    #>   window_plot_temp_compare : .plot_df_heatmap_diff: no visible global
    #>     function definition for ‘colorRampPalette’
    #>   window_plot_temp_compare : .plot_df_heatmap_diff: no visible global
    #>     function definition for ‘head’
    #>   window_plot_temp_compare : .plot_df_heatmap_diff: no visible global
    #>     function definition for ‘.filled.contour’
    #>   window_plot_temp_compare : plot_layout: no visible global function
    #>     definition for ‘plot’
    #>   window_plot_temp_compare : axis_layout: no visible global function
    #>     definition for ‘axis’
    #>   window_plot_temp_compare : axis_layout: no visible global function
    #>     definition for ‘par’
    #>   window_plot_temp_compare : color_key: no visible global function
    #>     definition for ‘plot’
    #>   window_plot_temp_compare : color_key: no visible global function
    #>     definition for ‘par’
    #>   window_plot_temp_compare : color_key: no visible global function
    #>     definition for ‘axis’
    #>   window_plot_temp_compare : color_key: no visible global function
    #>     definition for ‘polygon’
    #>   window_plot_temp_compare : color_key: no visible global function
    #>     definition for ‘text’
    #>   window_plot_temp_compare : color_key_diff: no visible global function
    #>     definition for ‘plot’
    #>   window_plot_temp_compare : color_key_diff: no visible global function
    #>     definition for ‘par’
    #>   window_plot_temp_compare : color_key_diff: no visible global function
    #>     definition for ‘axis’
    #>   window_plot_temp_compare : color_key_diff: no visible global function
    #>     definition for ‘polygon’
    #>   window_plot_temp_compare : color_key_diff: no visible global function
    #>     definition for ‘text’
    #>   window_plot_temp_compare: no visible global function definition for
    #>     ‘compare_to_field’
    #>   window_plot_temp_compare: no visible global function definition for
    #>     ‘dev.copy’
    #>   window_plot_temp_compare: no visible binding for global variable ‘pdf’
    #>   window_plot_temp_compare: no visible global function definition for
    #>     ‘dev.off’
    #>   window_plot_temp_compare: no visible global function definition for
    #>     ‘points’
    #>   window_plot_temp_compare: no visible global function definition for
    #>     ‘text’
    #>   window_select_SI_calculation: no visible global function definition for
    #>     ‘gwindow’
    #>   window_select_SI_calculation: no visible global function definition for
    #>     ‘ggroup’
    #>   window_select_SI_calculation: no visible global function definition for
    #>     ‘glabel’
    #>   window_select_SI_calculation: no visible global function definition for
    #>     ‘font<-’
    #>   window_select_SI_calculation: no visible global function definition for
    #>     ‘gcheckbox’
    #>   window_select_SI_calculation: no visible global function definition for
    #>     ‘gseparator’
    #>   window_select_SI_calculation: no visible global function definition for
    #>     ‘gradio’
    #>   window_select_SI_calculation: no visible global function definition for
    #>     ‘gbutton’
    #>   window_select_SI_calculation : <anonymous>: no visible binding for
    #>     global variable ‘dir_field_temp’
    #>   window_select_SI_calculation : <anonymous>: no visible global function
    #>     definition for ‘svalue’
    #>   window_select_SI_calculation : <anonymous>: no visible binding for
    #>     global variable ‘dir_field_level’
    #>   window_select_SI_calculation : <anonymous>: no visible global function
    #>     definition for ‘enabled<-’
    #>   window_select_SI_calculation : <anonymous>: no visible global function
    #>     definition for ‘svalue<-’
    #>   window_select_SI_calculation : <anonymous>: no visible binding for
    #>     global variable ‘label_status_SI_calculation’
    #>   window_select_SI_calculation : <anonymous>: no visible global function
    #>     definition for ‘dispose’
    #>   window_select_SI_calculation: no visible binding for '<<-' assignment
    #>     to ‘label_status_SI_calculation’
    #>   window_select_SI_calculation: no visible global function definition for
    #>     ‘visible<-’
    #>   window_select_auto_kalib: no visible global function definition for
    #>     ‘gwindow’
    #>   window_select_auto_kalib: no visible global function definition for
    #>     ‘ggroup’
    #>   window_select_auto_kalib: no visible global function definition for
    #>     ‘glabel’
    #>   window_select_auto_kalib: no visible global function definition for
    #>     ‘font<-’
    #>   window_select_auto_kalib: no visible global function definition for
    #>     ‘gcheckbox’
    #>   window_select_auto_kalib: no visible global function definition for
    #>     ‘gseparator’
    #>   window_select_auto_kalib: no visible global function definition for
    #>     ‘gradio’
    #>   window_select_auto_kalib: no visible global function definition for
    #>     ‘gslider’
    #>   window_select_auto_kalib: no visible global function definition for
    #>     ‘svalue’
    #>   window_select_auto_kalib: no visible global function definition for
    #>     ‘svalue<-’
    #>   window_select_auto_kalib: no visible global function definition for
    #>     ‘gbutton’
    #>   window_select_auto_kalib : <anonymous>: no visible binding for global
    #>     variable ‘boundary.env’
    #>   window_select_auto_kalib: no visible binding for '<<-' assignment to
    #>     ‘but_cal_si_auto’
    #>   window_select_auto_kalib : <anonymous>: no visible binding for global
    #>     variable ‘dir_field_temp’
    #>   window_select_auto_kalib : <anonymous>: no visible global function
    #>     definition for ‘svalue’
    #>   window_select_auto_kalib : <anonymous>: no visible binding for global
    #>     variable ‘dir_field_level’
    #>   window_select_auto_kalib : <anonymous>: no visible global function
    #>     definition for ‘enabled<-’
    #>   window_select_auto_kalib : <anonymous>: no visible global function
    #>     definition for ‘svalue<-’
    #>   window_select_auto_kalib : <anonymous>: no visible binding for global
    #>     variable ‘label_status_CAL_calculation’
    #>   window_select_auto_kalib : <anonymous>: no visible global function
    #>     definition for ‘dispose’
    #>   window_select_auto_kalib: no visible binding for '<<-' assignment to
    #>     ‘label_status_CAL_calculation’
    #>   window_select_auto_kalib: no visible global function definition for
    #>     ‘visible<-’
    #>   windows_main_menu: no visible global function definition for ‘gwindow’
    #>   windows_main_menu: no visible global function definition for ‘ggroup’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘workspace’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘arg_meteo’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘multi_inflow’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘multi_outflow’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘arg_inflow’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘arg_outflow’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘dir_field_temp’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘dir_field_level’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘List_parameter’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘List_values’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘dfList_Temp’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘dfList_Level’
    #>   windows_main_menu: no visible global function definition for ‘glabel’
    #>   windows_main_menu: no visible global function definition for ‘font<-’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘label_workspace’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘label_workspace_project’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘button_new_workspace’
    #>   windows_main_menu: no visible global function definition for ‘gbutton’
    #>   windows_main_menu : <anonymous>: no visible global function definition
    #>     for ‘tk_choose.dir’
    #>   windows_main_menu : <anonymous>: no visible global function definition
    #>     for ‘svalue<-’
    #>   windows_main_menu : <anonymous>: no visible binding for '<<-'
    #>     assignment to ‘workspace’
    #>   windows_main_menu : <anonymous>: no visible global function definition
    #>     for ‘read_nml’
    #>   windows_main_menu : <anonymous>: no visible global function definition
    #>     for ‘write_nml’
    #>   windows_main_menu : <anonymous>: no visible binding for global variable
    #>     ‘workspace’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘button_workspace’
    #>   windows_main_menu : <anonymous>: no visible global function definition
    #>     for ‘gwindow’
    #>   windows_main_menu : <anonymous>: no visible global function definition
    #>     for ‘ggroup’
    #>   windows_main_menu : <anonymous>: no visible global function definition
    #>     for ‘gimage’
    #>   windows_main_menu : <anonymous>: no visible global function definition
    #>     for ‘glabel’
    #>   windows_main_menu : <anonymous>: no visible global function definition
    #>     for ‘gbutton’
    #>   windows_main_menu : <anonymous> : <anonymous>: no visible global
    #>     function definition for ‘read_nml’
    #>   windows_main_menu : <anonymous> : <anonymous>: no visible global
    #>     function definition for ‘write_nml’
    #>   windows_main_menu : <anonymous> : <anonymous>: no visible binding for
    #>     global variable ‘workspace’
    #>   windows_main_menu : <anonymous> : <anonymous>: no visible global
    #>     function definition for ‘dispose’
    #>   windows_main_menu: no visible global function definition for
    #>     ‘gseparator’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘label_met_data’
    #>   windows_main_menu : <anonymous>: no visible binding for global variable
    #>     ‘dir_meteo’
    #>   windows_main_menu : <anonymous>: no visible binding for global variable
    #>     ‘arg_meteo’
    #>   windows_main_menu: no visible global function definition for
    #>     ‘enabled<-’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘label_inflow_data’
    #>   windows_main_menu : <anonymous>: no visible binding for global variable
    #>     ‘multi_inflow’
    #>   windows_main_menu : <anonymous>: no visible binding for global variable
    #>     ‘dir_inflow’
    #>   windows_main_menu : <anonymous>: no visible binding for global variable
    #>     ‘arg_inflow’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘label_outflow_data’
    #>   windows_main_menu : <anonymous>: no visible binding for global variable
    #>     ‘multi_outflow’
    #>   windows_main_menu : <anonymous>: no visible binding for global variable
    #>     ‘dir_outflow’
    #>   windows_main_menu : <anonymous>: no visible binding for global variable
    #>     ‘arg_outflow’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘label_nml_status’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘label_nml_range’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘button_field_temp’
    #>   windows_main_menu : <anonymous>: no visible global function definition
    #>     for ‘tk_choose.files’
    #>   windows_main_menu : <anonymous>: no visible binding for '<<-'
    #>     assignment to ‘dir_field_temp’
    #>   windows_main_menu : <anonymous>: no visible binding for global variable
    #>     ‘dir_field_temp’
    #>   windows_main_menu : <anonymous>: no visible global function definition
    #>     for ‘enabled<-’
    #>   windows_main_menu: no visible binding for global variable
    #>     ‘button_field_temp’
    #>   windows_main_menu: no visible global function definition for
    #>     ‘gcheckbox’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘label_field_level’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘button_field_level’
    #>   windows_main_menu : <anonymous>: no visible binding for '<<-'
    #>     assignment to ‘dir_field_level’
    #>   windows_main_menu : <anonymous>: no visible binding for global variable
    #>     ‘dir_field_level’
    #>   windows_main_menu: no visible binding for global variable
    #>     ‘button_field_level’
    #>   windows_main_menu: no visible binding for '<<-' assignment to
    #>     ‘label_status_build’
    #>   windows_main_menu : <anonymous>: no visible global function definition
    #>     for ‘svalue’
    #>   windows_main_menu : <anonymous>: no visible global function definition
    #>     for ‘get_nml_value’
    #>   windows_main_menu : <anonymous>: no visible global function definition
    #>     for ‘gmessage’
    #>   windows_main_menu : <anonymous>: no visible global function definition
    #>     for ‘dispose’
    #>   windows_main_menu: no visible global function definition for
    #>     ‘visible<-’
    #>   Undefined global functions or variables:
    #>     .filled.contour .simple_layout List_parameter List_parameter_temp
    #>     List_values add addHandlerClicked addSpring aov arg_inflow arg_meteo
    #>     arg_outflow axis barplot boundary.env but_cal_si_auto
    #>     button_autocalib button_build button_cal_SI_value button_confi
    #>     button_field_level button_field_temp button_set_parameter cb
    #>     checkbox_Level_plot checkbox_Level_rmse checkbox_Temp_plot
    #>     checkbox_Temp_plot2 checkbox_Temp_plot3 checkbox_Temp_plot4
    #>     checkbox_Temp_rmse colorRampPalette compare_to_field dev.copy dev.cur
    #>     dev.off dev.set dir_field_level dir_field_temp dir_inflow dir_meteo
    #>     dir_outflow dir_output dispose enabled<- font<- galert gbutton
    #>     gcheckbox gcombobox gedit get.offsets get_nml_value get_var gewaehlt
    #>     gewaehlterwert gframe ggraphics ggroup gimage glabel gmessage gradio
    #>     gseparator gslider gwindow head hist install.packages interp k l
    #>     label_inflow_data label_met_data label_nml_range label_outflow_data
    #>     label_status_CAL_calculation label_status_SI_calculation
    #>     label_status_build layout legend lines list_0_data list_missing_data
    #>     lowess multi_inflow multi_outflow n2mfrow na.kalman na.omit par pdf
    #>     plot plot_var png points polygon read.csv read_nml resample_sim
    #>     resample_to_field run_glm set_nml shapiro.test sim_vars stack
    #>     strwidth svalue svalue<- text tk_choose.dir tk_choose.files
    #>     valid_fig_path visible<- workspace write.csv write.table write_nml
    #>   Consider adding
    #>     importFrom("grDevices", "colorRampPalette", "dev.copy", "dev.cur",
    #>                "dev.off", "dev.set", "n2mfrow", "pdf", "png")
    #>     importFrom("graphics", ".filled.contour", "axis", "barplot", "hist",
    #>                "layout", "legend", "lines", "par", "plot", "points",
    #>                "polygon", "strwidth", "text")
    #>     importFrom("stats", "aov", "lowess", "na.omit", "shapiro.test")
    #>     importFrom("utils", "head", "install.packages", "read.csv", "stack",
    #>                "write.csv", "write.table")
    #>   to your NAMESPACE file.
    #> 
    #> 0 errors ✔ | 2 warnings ✖ | 1 note ✖
    #> Error: R CMD check found WARNINGs

</details>
