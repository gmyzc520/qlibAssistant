# params 
 {'predict_dates': [{'start': '2026-04-29', 'end': '2026-04-29'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260429_17 109514819636661433 (Recorders: 2/5)

	Recorder: 861839d7ba5c481c83eb1619f66221ca

		Model: {'id': '861839d7ba5c481c83eb1619f66221ca', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.06, 'Rank IC': 0.014, 'Rank ICIR': 0.142}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.142', 'weight': '0.092'}

	Recorder: 395e9cbd582641b3bd7aee03a74fda20

		Model: {'id': '395e9cbd582641b3bd7aee03a74fda20', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.185, 'Rank IC': 0.009, 'Rank ICIR': 0.056}, 'data_train_vec': ['2025-04-29', '2026-01-28'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.056', 'weight': '0.036'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260429_17 810636064540214695 (Recorders: 2/5)

	Recorder: 740c1fb277d54ed184b5703dfdcd3dd9

		Model: {'id': '740c1fb277d54ed184b5703dfdcd3dd9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.082, 'Rank IC': 0.012, 'Rank ICIR': 0.111}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.111', 'weight': '0.072'}

	Recorder: 2d71672531fe44828417991ea0cadb56

		Model: {'id': '2d71672531fe44828417991ea0cadb56', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.063, 'ICIR': 0.543, 'Rank IC': 0.031, 'Rank ICIR': 0.232}, 'data_train_vec': ['2025-04-29', '2026-01-28'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.232', 'weight': '0.150'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260429_14 723742651012080150 (Recorders: 2/5)

	Recorder: d849d9c358bc4ad59d3d45aea3ca6690

		Model: {'id': 'd849d9c358bc4ad59d3d45aea3ca6690', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.059, 'Rank IC': 0.04, 'Rank ICIR': 0.244}, 'data_train_vec': ['2023-04-29', '2025-07-28'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.244', 'weight': '0.157'}

	Recorder: 767afdfa4e684fb6b6b472c7d230e012

		Model: {'id': '767afdfa4e684fb6b6b472c7d230e012', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.197, 'Rank IC': 0.008, 'Rank ICIR': 0.049}, 'data_train_vec': ['2025-04-29', '2026-01-28'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.049', 'weight': '0.032'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260429_14 869078571425570826 (Recorders: 2/5)

	Recorder: 769c816ec8a24851bbe2050c9906ca7d

		Model: {'id': '769c816ec8a24851bbe2050c9906ca7d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.031, 'Rank IC': 0.01, 'Rank ICIR': 0.084}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.084', 'weight': '0.054'}

	Recorder: fe642209d6c54d8dbe3f406ba7f09eae

		Model: {'id': 'fe642209d6c54d8dbe3f406ba7f09eae', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.068, 'ICIR': 0.626, 'Rank IC': 0.042, 'Rank ICIR': 0.342}, 'data_train_vec': ['2025-04-29', '2026-01-28'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.342', 'weight': '0.221'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260429_14 524558846578450804 (Recorders: 2/5)

	Recorder: 42c5ef2493194c46bf50ba0b8ef0f0f2

		Model: {'id': '42c5ef2493194c46bf50ba0b8ef0f0f2', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.06, 'Rank IC': 0.02, 'Rank ICIR': 0.177}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.177', 'weight': '0.114'}

	Recorder: d2a085e9b507449c9e07a53886bbe5ab

		Model: {'id': 'd2a085e9b507449c9e07a53886bbe5ab', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.188, 'Rank IC': 0.014, 'Rank ICIR': 0.113}, 'data_train_vec': ['2025-04-29', '2026-01-28'], 'train_time_vec': ['2026-04-29', '2026-04-29'], 'rank_icir': '0.113', 'weight': '0.073'}
