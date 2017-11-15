Data Dictionary
#site_barcode
##Type: id
##Description: unique identifier for each pump installation
local_date, id, date at location of pump installation
nevents, feature, number of events recorded
naive_failure, feature, indicator number of events < 10
nevents_overall_cluster_percent_log, feature, log-fold difference in number of events relative to expected defined using k-means clustering
nevents_overall_simple_percent_log, feature, log-fold difference in number of events relative to expected defined as mean
nevents_wd_cluster_percent_log, feature, log-fold difference in number of events relative to expected defined using k-means clustering per day of week
nevents_wd_simple_percent_log, feature, log-fold difference in number of events relative to expected defined as mean per day of week
duration, feature, total duration of all pumping events
pf_overall_stl_seasonal_percent_log, feature, log-fold difference in pump function relative to stl regression with weekly seasonality
pf_wd_simple_percent_log, feature, log-fold difference in pump function relative to expected defined as mean per day of week
flow_overall_stl_seasonal_percent_log, feature, log-fold difference in flow rate relative to stl regression with weekly seasonality
nevents_overall_stl_seasonal_percent_log, log-fold difference in number of events relative to stl regression with weekly seasonality
fail_next_week, outcome, indicator that the pump will fail in the next seven days (including current date)
pred_fail_next_week_SL, prediction,  predicted probability of forecasted failure using SuperLearner (cross-validated)
currently_failed, outcome, indicator that the pump is currently failed
pred_currently_failed_SL, prediction, predicted probability of currently failure using SuperLearner (cross-validated)
pred_fail_next_week_SL, prediction, predicted probability of forecasted failure using GLM (cross-validated)
pred_currently_failed_SL, prediction, predicted probability of currently failure using GLM (cross-validated)