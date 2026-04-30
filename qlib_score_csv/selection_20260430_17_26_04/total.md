# params 
 {'predict_dates': [{'start': '2026-04-30', 'end': '2026-04-30'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260430_17 951839238724634507 (Recorders: 2/5)

	Recorder: 381fba6be5cf43b997040b4bd0d33977

		Model: {'id': '381fba6be5cf43b997040b4bd0d33977', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.06, 'Rank IC': 0.013, 'Rank ICIR': 0.127}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.127', 'weight': '0.088'}

	Recorder: 9bf94f593de44a218759932fe226054f

		Model: {'id': '9bf94f593de44a218759932fe226054f', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.047, 'ICIR': 0.406, 'Rank IC': 0.019, 'Rank ICIR': 0.167}, 'data_train_vec': ['2025-04-30', '2026-01-29'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.167', 'weight': '0.115'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260430_16 884953850786799491 (Recorders: 2/5)

	Recorder: aad3c13fd8484089b56988f56c72be6e

		Model: {'id': 'aad3c13fd8484089b56988f56c72be6e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.058, 'Rank IC': 0.01, 'Rank ICIR': 0.086}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.086', 'weight': '0.059'}

	Recorder: 566d6070768f4194a9d9f723d2ec1dca

		Model: {'id': '566d6070768f4194a9d9f723d2ec1dca', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.075, 'ICIR': 0.643, 'Rank IC': 0.035, 'Rank ICIR': 0.287}, 'data_train_vec': ['2025-04-30', '2026-01-29'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.287', 'weight': '0.198'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260430_14 396839648357099702 (Recorders: 2/5)

	Recorder: f5ad54d2b3854a98a0a49aac531be7a9

		Model: {'id': 'f5ad54d2b3854a98a0a49aac531be7a9', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.091, 'Rank IC': 0.002, 'Rank ICIR': 0.02}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.020', 'weight': '0.014'}

	Recorder: 804fd482eb254d488278a1f61142f9ef

		Model: {'id': '804fd482eb254d488278a1f61142f9ef', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.272, 'Rank IC': 0.012, 'Rank ICIR': 0.08}, 'data_train_vec': ['2025-04-30', '2026-01-29'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.080', 'weight': '0.055'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260430_14 536324454481018272 (Recorders: 2/5)

	Recorder: 5f53d71344bb47779cbe2f03440d08e5

		Model: {'id': '5f53d71344bb47779cbe2f03440d08e5', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.022, 'Rank IC': 0.009, 'Rank ICIR': 0.072}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.072', 'weight': '0.050'}

	Recorder: 49787218d503405ab4126fd44e61dd0f

		Model: {'id': '49787218d503405ab4126fd44e61dd0f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.057, 'ICIR': 0.598, 'Rank IC': 0.03, 'Rank ICIR': 0.273}, 'data_train_vec': ['2025-04-30', '2026-01-29'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.273', 'weight': '0.188'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260430_14 671903527743298287 (Recorders: 3/5)

	Recorder: 30804a8b6bd544d0b0c00532dde9a0f7

		Model: {'id': '30804a8b6bd544d0b0c00532dde9a0f7', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.043, 'Rank IC': 0.013, 'Rank ICIR': 0.075}, 'data_train_vec': ['2021-04-30', '2025-01-29'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.075', 'weight': '0.052'}

	Recorder: 8e3f24f41586495984e3809fc2efdc4b

		Model: {'id': '8e3f24f41586495984e3809fc2efdc4b', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.049, 'Rank IC': 0.017, 'Rank ICIR': 0.145}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.145', 'weight': '0.100'}

	Recorder: 795fd93ca4124291831ea603fb27f3c7

		Model: {'id': '795fd93ca4124291831ea603fb27f3c7', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.271, 'Rank IC': 0.01, 'Rank ICIR': 0.118}, 'data_train_vec': ['2025-04-30', '2026-01-29'], 'train_time_vec': ['2026-04-30', '2026-04-30'], 'rank_icir': '0.118', 'weight': '0.081'}
