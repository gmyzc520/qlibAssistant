# params 
 {'predict_dates': [{'start': '2026-05-18', 'end': '2026-05-18'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260518_18 463087841345253631 (Recorders: 4/5)

	Recorder: 46f3390c823347859c94839aabf74fbe

		Model: {'id': '46f3390c823347859c94839aabf74fbe', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.095, 'Rank IC': 0.016, 'Rank ICIR': 0.12}, 'data_train_vec': ['2021-05-18', '2025-02-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.120', 'weight': '0.043'}

	Recorder: f908a261cb90464c82a5e0e3a4ab5fee

		Model: {'id': 'f908a261cb90464c82a5e0e3a4ab5fee', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.059, 'Rank IC': 0.014, 'Rank ICIR': 0.09}, 'data_train_vec': ['2022-05-18', '2025-05-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.090', 'weight': '0.032'}

	Recorder: 9a39cb150e1748b7835d833e3a0d12cc

		Model: {'id': '9a39cb150e1748b7835d833e3a0d12cc', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.092, 'Rank IC': 0.023, 'Rank ICIR': 0.147}, 'data_train_vec': ['2023-05-18', '2025-08-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.147', 'weight': '0.052'}

	Recorder: cc04d8cb1981474e80f96ac423f46614

		Model: {'id': 'cc04d8cb1981474e80f96ac423f46614', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.043, 'ICIR': 0.272, 'Rank IC': 0.039, 'Rank ICIR': 0.232}, 'data_train_vec': ['2025-05-18', '2026-02-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.232', 'weight': '0.082'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260518_18 971436355057949386 (Recorders: 3/5)

	Recorder: 9a4c81f927e847959edb6dac4dd57362

		Model: {'id': '9a4c81f927e847959edb6dac4dd57362', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.143, 'Rank IC': 0.026, 'Rank ICIR': 0.203}, 'data_train_vec': ['2023-05-18', '2025-08-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.203', 'weight': '0.072'}

	Recorder: eeee4e2ab3be49b08297701222dfd146

		Model: {'id': 'eeee4e2ab3be49b08297701222dfd146', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.114, 'Rank IC': 0.003, 'Rank ICIR': 0.034}, 'data_train_vec': ['2024-05-18', '2025-11-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.034', 'weight': '0.012'}

	Recorder: d7c71455bf324a04b9c0ad73bdbea667

		Model: {'id': 'd7c71455bf324a04b9c0ad73bdbea667', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.095, 'ICIR': 0.595, 'Rank IC': 0.048, 'Rank ICIR': 0.277}, 'data_train_vec': ['2025-05-18', '2026-02-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.277', 'weight': '0.098'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260518_16 421287106639472347 (Recorders: 2/5)

	Recorder: 5322cbc421a840b6baf7599d5097019d

		Model: {'id': '5322cbc421a840b6baf7599d5097019d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.111, 'Rank IC': 0.036, 'Rank ICIR': 0.23}, 'data_train_vec': ['2023-05-18', '2025-08-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.230', 'weight': '0.082'}

	Recorder: 0ffd1b26233d49a1a26205303b765bbc

		Model: {'id': '0ffd1b26233d49a1a26205303b765bbc', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.068, 'ICIR': 0.392, 'Rank IC': 0.034, 'Rank ICIR': 0.186}, 'data_train_vec': ['2025-05-18', '2026-02-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.186', 'weight': '0.066'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260518_16 150893277876244004 (Recorders: 4/5)

	Recorder: 78232e9715bb4c2c8ee650927f185f37

		Model: {'id': '78232e9715bb4c2c8ee650927f185f37', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.035, 'Rank IC': 0.027, 'Rank ICIR': 0.241}, 'data_train_vec': ['2021-05-18', '2025-02-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.241', 'weight': '0.086'}

	Recorder: da884f1776fc429d8901ba4dd6cfaac9

		Model: {'id': 'da884f1776fc429d8901ba4dd6cfaac9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.071, 'Rank IC': 0.034, 'Rank ICIR': 0.304}, 'data_train_vec': ['2023-05-18', '2025-08-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.304', 'weight': '0.108'}

	Recorder: b82b480d02ec4c1da451be3d2d781549

		Model: {'id': 'b82b480d02ec4c1da451be3d2d781549', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.04, 'Rank IC': 0.015, 'Rank ICIR': 0.132}, 'data_train_vec': ['2024-05-18', '2025-11-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.132', 'weight': '0.047'}

	Recorder: 6f1e2e5952894b8c9abb4f2eedd9c18a

		Model: {'id': '6f1e2e5952894b8c9abb4f2eedd9c18a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.069, 'ICIR': 0.485, 'Rank IC': 0.043, 'Rank ICIR': 0.265}, 'data_train_vec': ['2025-05-18', '2026-02-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.265', 'weight': '0.094'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260518_15 399961787711414712 (Recorders: 2/5)

	Recorder: ca7288446eae48eb93dc2aec1560a4d3

		Model: {'id': 'ca7288446eae48eb93dc2aec1560a4d3', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.082, 'Rank IC': 0.027, 'Rank ICIR': 0.169}, 'data_train_vec': ['2023-05-18', '2025-08-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.169', 'weight': '0.060'}

	Recorder: 83eb473e591a4caea2f6748d6afea8d7

		Model: {'id': '83eb473e591a4caea2f6748d6afea8d7', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.217, 'Rank IC': 0.031, 'Rank ICIR': 0.187}, 'data_train_vec': ['2025-05-18', '2026-02-17'], 'train_time_vec': ['2026-05-18', '2026-05-18'], 'rank_icir': '0.187', 'weight': '0.066'}
