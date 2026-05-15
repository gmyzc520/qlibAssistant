# params 
 {'predict_dates': [{'start': '2026-05-15', 'end': '2026-05-15'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260515_17 155336628414413842 (Recorders: 3/5)

	Recorder: 45e889bee37e4c70a5828c9a0caa0676

		Model: {'id': '45e889bee37e4c70a5828c9a0caa0676', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.032, 'Rank IC': 0.02, 'Rank ICIR': 0.128}, 'data_train_vec': ['2022-05-15', '2025-05-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.128', 'weight': '0.057'}

	Recorder: d50e45b25092454f9cf0c799bde0a8ba

		Model: {'id': 'd50e45b25092454f9cf0c799bde0a8ba', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.022, 'Rank ICIR': 0.143}, 'data_train_vec': ['2023-05-15', '2025-08-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.143', 'weight': '0.064'}

	Recorder: f505307093014515bccc786897f6cccb

		Model: {'id': 'f505307093014515bccc786897f6cccb', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.081, 'ICIR': 0.54, 'Rank IC': 0.043, 'Rank ICIR': 0.267}, 'data_train_vec': ['2025-05-15', '2026-02-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.267', 'weight': '0.119'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260515_16 773413871494511954 (Recorders: 2/5)

	Recorder: 6ca0cd42cf854feba643c88713b24ac1

		Model: {'id': '6ca0cd42cf854feba643c88713b24ac1', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.165, 'Rank IC': 0.021, 'Rank ICIR': 0.181}, 'data_train_vec': ['2023-05-15', '2025-08-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.181', 'weight': '0.081'}

	Recorder: 0bf66bf29e9745468707e80e3eba7f23

		Model: {'id': '0bf66bf29e9745468707e80e3eba7f23', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.079, 'ICIR': 0.503, 'Rank IC': 0.026, 'Rank ICIR': 0.156}, 'data_train_vec': ['2025-05-15', '2026-02-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.156', 'weight': '0.070'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260515_14 968672631450538265 (Recorders: 3/5)

	Recorder: 72885b2fcae44204a9d5a73474751a06

		Model: {'id': '72885b2fcae44204a9d5a73474751a06', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.024, 'Rank IC': 0.03, 'Rank ICIR': 0.164}, 'data_train_vec': ['2022-05-15', '2025-05-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.164', 'weight': '0.073'}

	Recorder: 8af5413bf01941ac86504e5f00631900

		Model: {'id': '8af5413bf01941ac86504e5f00631900', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.111, 'Rank IC': 0.034, 'Rank ICIR': 0.225}, 'data_train_vec': ['2023-05-15', '2025-08-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.225', 'weight': '0.101'}

	Recorder: 844d733833714534959eb19416889f83

		Model: {'id': '844d733833714534959eb19416889f83', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.065, 'ICIR': 0.397, 'Rank IC': 0.022, 'Rank ICIR': 0.128}, 'data_train_vec': ['2025-05-15', '2026-02-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.128', 'weight': '0.057'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260515_14 562987066616980334 (Recorders: 3/5)

	Recorder: bf3faccbc97245c1850455a38f91bb87

		Model: {'id': 'bf3faccbc97245c1850455a38f91bb87', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.037, 'Rank IC': 0.029, 'Rank ICIR': 0.266}, 'data_train_vec': ['2023-05-15', '2025-08-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.266', 'weight': '0.119'}

	Recorder: f22f9a337c394a38a31412dfaece4b4c

		Model: {'id': 'f22f9a337c394a38a31412dfaece4b4c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.042, 'Rank IC': 0.016, 'Rank ICIR': 0.142}, 'data_train_vec': ['2024-05-15', '2025-11-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.142', 'weight': '0.064'}

	Recorder: 0d7eebb2b20d457287687a1bfbb2de5e

		Model: {'id': '0d7eebb2b20d457287687a1bfbb2de5e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.075, 'ICIR': 0.594, 'Rank IC': 0.044, 'Rank ICIR': 0.313}, 'data_train_vec': ['2025-05-15', '2026-02-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.313', 'weight': '0.140'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260515_14 210435238141746689 (Recorders: 1/5)

	Recorder: 59b78b2f69c64c3996a12857e7f68901

		Model: {'id': '59b78b2f69c64c3996a12857e7f68901', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.044, 'ICIR': 0.337, 'Rank IC': 0.017, 'Rank ICIR': 0.123}, 'data_train_vec': ['2025-05-15', '2026-02-14'], 'train_time_vec': ['2026-05-15', '2026-05-15'], 'rank_icir': '0.123', 'weight': '0.055'}
