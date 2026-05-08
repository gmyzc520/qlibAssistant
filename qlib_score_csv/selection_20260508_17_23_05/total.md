# params 
 {'predict_dates': [{'start': '2026-05-08', 'end': '2026-05-08'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260508_16 580425407149576970 (Recorders: 2/5)

	Recorder: 665a7bd9d8c64b8493dbf31de75ed37a

		Model: {'id': '665a7bd9d8c64b8493dbf31de75ed37a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.131, 'Rank IC': 0.039, 'Rank ICIR': 0.239}, 'data_train_vec': ['2023-05-08', '2025-08-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.239', 'weight': '0.091'}

	Recorder: 36ffb2b0ea684f02a575fba1d2bbfbde

		Model: {'id': '36ffb2b0ea684f02a575fba1d2bbfbde', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.235, 'Rank IC': 0.02, 'Rank ICIR': 0.146}, 'data_train_vec': ['2025-05-08', '2026-02-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.146', 'weight': '0.056'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260508_16 722850439196764926 (Recorders: 2/5)

	Recorder: 5e3056a29247421a95948c8f8aaee45e

		Model: {'id': '5e3056a29247421a95948c8f8aaee45e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.159, 'Rank IC': 0.019, 'Rank ICIR': 0.157}, 'data_train_vec': ['2024-05-08', '2025-11-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.157', 'weight': '0.060'}

	Recorder: bb73c4b9241d46aa87b2e183f6492e7a

		Model: {'id': 'bb73c4b9241d46aa87b2e183f6492e7a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.075, 'ICIR': 0.508, 'Rank IC': 0.02, 'Rank ICIR': 0.146}, 'data_train_vec': ['2025-05-08', '2026-02-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.146', 'weight': '0.056'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260508_14 372240351100624014 (Recorders: 4/5)

	Recorder: e7484ad53bf24ad7aa9d1cda45f69692

		Model: {'id': 'e7484ad53bf24ad7aa9d1cda45f69692', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.04, 'Rank IC': 0.032, 'Rank ICIR': 0.179}, 'data_train_vec': ['2022-05-08', '2025-05-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.179', 'weight': '0.068'}

	Recorder: f1a9f735456545d3849a694f99f695d7

		Model: {'id': 'f1a9f735456545d3849a694f99f695d7', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.049, 'Rank IC': 0.029, 'Rank ICIR': 0.177}, 'data_train_vec': ['2023-05-08', '2025-08-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.177', 'weight': '0.067'}

	Recorder: fcbfe23063d943d186394e7b153b8131

		Model: {'id': 'fcbfe23063d943d186394e7b153b8131', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.055, 'Rank IC': 0.013, 'Rank ICIR': 0.106}, 'data_train_vec': ['2024-05-08', '2025-11-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.106', 'weight': '0.040'}

	Recorder: 85b116b5213d48af882ee6ad25170d45

		Model: {'id': '85b116b5213d48af882ee6ad25170d45', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.051, 'ICIR': 0.388, 'Rank IC': 0.015, 'Rank ICIR': 0.111}, 'data_train_vec': ['2025-05-08', '2026-02-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.111', 'weight': '0.042'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260508_14 873264108720171935 (Recorders: 4/5)

	Recorder: 758038acd5cf43e08a396311b13aaf31

		Model: {'id': '758038acd5cf43e08a396311b13aaf31', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.03, 'Rank IC': 0.019, 'Rank ICIR': 0.17}, 'data_train_vec': ['2021-05-08', '2025-02-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.170', 'weight': '0.065'}

	Recorder: 0de7fafb7d124c38a1e4241bba23f5dc

		Model: {'id': '0de7fafb7d124c38a1e4241bba23f5dc', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.012, 'Rank IC': 0.026, 'Rank ICIR': 0.209}, 'data_train_vec': ['2022-05-08', '2025-05-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.209', 'weight': '0.080'}

	Recorder: df15e7cd4d71456b851dc08397b3a8be

		Model: {'id': 'df15e7cd4d71456b851dc08397b3a8be', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.058, 'Rank IC': 0.02, 'Rank ICIR': 0.181}, 'data_train_vec': ['2024-05-08', '2025-11-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.181', 'weight': '0.069'}

	Recorder: d82f11e778cf4cb0ac757679f50df8fd

		Model: {'id': 'd82f11e778cf4cb0ac757679f50df8fd', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.054, 'ICIR': 0.513, 'Rank IC': 0.023, 'Rank ICIR': 0.19}, 'data_train_vec': ['2025-05-08', '2026-02-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.190', 'weight': '0.072'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260508_14 102388938969993559 (Recorders: 3/5)

	Recorder: 9c1f8f39209e47829fae44c415ca1555

		Model: {'id': '9c1f8f39209e47829fae44c415ca1555', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.015, 'Rank IC': 0.022, 'Rank ICIR': 0.131}, 'data_train_vec': ['2023-05-08', '2025-08-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.131', 'weight': '0.050'}

	Recorder: 4b674b82cc9a4a2eb99196dc79cc236e

		Model: {'id': '4b674b82cc9a4a2eb99196dc79cc236e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.027, 'Rank IC': 0.012, 'Rank ICIR': 0.099}, 'data_train_vec': ['2024-05-08', '2025-11-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.099', 'weight': '0.038'}

	Recorder: 275d9bbd61ad4f9882b143aaa4b0fd86

		Model: {'id': '275d9bbd61ad4f9882b143aaa4b0fd86', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.072, 'ICIR': 0.622, 'Rank IC': 0.042, 'Rank ICIR': 0.382}, 'data_train_vec': ['2025-05-08', '2026-02-07'], 'train_time_vec': ['2026-05-08', '2026-05-08'], 'rank_icir': '0.382', 'weight': '0.146'}
