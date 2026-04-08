# params 
 {'predict_dates': [{'start': '2026-04-08', 'end': '2026-04-08'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260408_16 532313045612751351 (Recorders: 3/5)

	Recorder: fc96622fadb640828529aafe67b707cb

		Model: {'id': 'fc96622fadb640828529aafe67b707cb', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.141, 'Rank IC': 0.045, 'Rank ICIR': 0.285}, 'data_train_vec': ['2023-04-08', '2025-07-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.285', 'weight': '0.082'}

	Recorder: 5698afca91084499bb99d368cebe75c2

		Model: {'id': '5698afca91084499bb99d368cebe75c2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.312, 'Rank IC': 0.035, 'Rank ICIR': 0.296}, 'data_train_vec': ['2024-04-08', '2025-10-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.296', 'weight': '0.085'}

	Recorder: 326b4555fb194909838c91afae5d3016

		Model: {'id': '326b4555fb194909838c91afae5d3016', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.144, 'Rank IC': 0.011, 'Rank ICIR': 0.071}, 'data_train_vec': ['2025-04-08', '2026-01-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.071', 'weight': '0.020'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260408_16 276254243779915016 (Recorders: 1/5)

	Recorder: eaeed43f309247fe9fe68317980257ac

		Model: {'id': 'eaeed43f309247fe9fe68317980257ac', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.322, 'Rank IC': 0.037, 'Rank ICIR': 0.311}, 'data_train_vec': ['2024-04-08', '2025-10-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.311', 'weight': '0.090'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260408_14 424971878755029810 (Recorders: 4/5)

	Recorder: d96cca0fd36c4a6a87f2e93e3bbf1373

		Model: {'id': 'd96cca0fd36c4a6a87f2e93e3bbf1373', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.044, 'Rank IC': 0.027, 'Rank ICIR': 0.152}, 'data_train_vec': ['2021-04-08', '2025-01-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.152', 'weight': '0.044'}

	Recorder: 38eaebedd4bb483fbd816bfa1526c985

		Model: {'id': '38eaebedd4bb483fbd816bfa1526c985', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.014, 'Rank IC': 0.031, 'Rank ICIR': 0.167}, 'data_train_vec': ['2022-04-08', '2025-04-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.167', 'weight': '0.048'}

	Recorder: c975fa8304134b9e818e8bc6472d5ba5

		Model: {'id': 'c975fa8304134b9e818e8bc6472d5ba5', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.139, 'Rank IC': 0.055, 'Rank ICIR': 0.32}, 'data_train_vec': ['2023-04-08', '2025-07-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.320', 'weight': '0.092'}

	Recorder: a06b25756fe5479082940bd10072a699

		Model: {'id': 'a06b25756fe5479082940bd10072a699', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.395, 'Rank IC': 0.037, 'Rank ICIR': 0.363}, 'data_train_vec': ['2024-04-08', '2025-10-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.363', 'weight': '0.105'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260408_14 849550960174299565 (Recorders: 5/5)

	Recorder: b432866b2941424398556380393ba75d

		Model: {'id': 'b432866b2941424398556380393ba75d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.111, 'Rank IC': 0.022, 'Rank ICIR': 0.183}, 'data_train_vec': ['2021-04-08', '2025-01-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.183', 'weight': '0.053'}

	Recorder: a93800b8778745eb9b1dc455f6cd4063

		Model: {'id': 'a93800b8778745eb9b1dc455f6cd4063', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.057, 'Rank IC': 0.025, 'Rank ICIR': 0.212}, 'data_train_vec': ['2022-04-08', '2025-04-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.212', 'weight': '0.061'}

	Recorder: 92506ca47ee24d3eb1ef091d9e8674da

		Model: {'id': '92506ca47ee24d3eb1ef091d9e8674da', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.153, 'Rank IC': 0.044, 'Rank ICIR': 0.38}, 'data_train_vec': ['2023-04-08', '2025-07-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.380', 'weight': '0.110'}

	Recorder: 0ecdace7e81a43ddbd4b2a77a3a0b82b

		Model: {'id': '0ecdace7e81a43ddbd4b2a77a3a0b82b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.067, 'Rank IC': 0.011, 'Rank ICIR': 0.092}, 'data_train_vec': ['2024-04-08', '2025-10-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.092', 'weight': '0.027'}

	Recorder: e7b9d1715dd8499ba1a50ec3ac4d34bd

		Model: {'id': 'e7b9d1715dd8499ba1a50ec3ac4d34bd', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.072, 'Rank IC': 0.006, 'Rank ICIR': 0.036}, 'data_train_vec': ['2025-04-08', '2026-01-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.036', 'weight': '0.010'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260408_13 253544889834392485 (Recorders: 3/5)

	Recorder: 319ec0b873284dd2950532389bd88ead

		Model: {'id': '319ec0b873284dd2950532389bd88ead', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.088, 'Rank IC': 0.025, 'Rank ICIR': 0.141}, 'data_train_vec': ['2021-04-08', '2025-01-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.141', 'weight': '0.041'}

	Recorder: 0de9a2f60ef047148282f603546221a5

		Model: {'id': '0de9a2f60ef047148282f603546221a5', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.035, 'Rank IC': 0.032, 'Rank ICIR': 0.189}, 'data_train_vec': ['2023-04-08', '2025-07-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.189', 'weight': '0.054'}

	Recorder: 9b9a6ff864e14448a02b52c324ee112f

		Model: {'id': '9b9a6ff864e14448a02b52c324ee112f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.301, 'Rank IC': 0.031, 'Rank ICIR': 0.27}, 'data_train_vec': ['2024-04-08', '2025-10-07'], 'train_time_vec': ['2026-04-08', '2026-04-08'], 'rank_icir': '0.270', 'weight': '0.078'}
